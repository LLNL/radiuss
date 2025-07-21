---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/13971568?"
user: becker33
date: 2025-07-20
repo_name: spack/spack
html_url: https://github.com/spack/spack/releases/tag/v1.0.0
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/becker33' target='_blank'>becker33</a> released <a href='https://github.com/spack/spack/releases/tag/v1.0.0' target='_blank'>v1.0.0</a>.

<small>`v1.0.0` is a major feature release and a significant milestone. It introduces compiler dependencies, a foundational change that has been in development for almost seven years, and the project's first stable package API.

If you are interested in more information, you can find more details on the road to v1.0, as well as its features, in talks from the 2025 Spack User Meeting. For example:
* [State of the Spack Community](https://www.youtube.com/watch?v=4rInmUfuiZQ&list=PLRKq_yxxHw29-JcpG2CZ-xKK2U8Hw8O1t&index=2)
* [Spack v1.0 overview](https://www.youtube.com/watch?v=nFksqSDNwQA&list=PLRKq_yxxHw29-JcpG2CZ-xKK2U8Hw8O1t&index=4)

Introducing some of these features required us to make breaking changes. In most cases, we've also provided tools (in the form of Spack commands) that you can use to automatically migrate your packages and configuration.

## Overview

- [Overview](#overview)
- [Stable Package API](#stable-package-api)
    - [Separate Package Repository](#separate-package-repository)
    - [Updating and Pinning Packages](#updating-and-pinning-packages)
    - [Breaking changes related to package repositories](#breaking-changes-related-to-package-repositories)
    - [Migrating to the new package API](#migrating-to-the-new-package-api)
- [Compiler dependencies](#compiler-dependencies)
    - [Compiler configuration](#compiler-configuration)
    - [Languages are virtual dependencies](#languages-are-virtual-dependencies)
    - [The meaning of % has changed](#the-meaning-of-%25-has-changed)
    - [Virtual assignment syntax](#virtual-assignment-syntax)
    - [Toolchains](#toolchains)
    - [Ordering of variants and compilers now matters](#ordering-of-variants-and-compilers-now-matters)
- [Additional Major Features](#additional-major-features)
    - [Concurrent Package Builds](#concurrent-package-builds)
    - [Content-addressed build caches](#content-addressed-build-caches)
    - [Better provenance and mirroring for git](#better-provenance-and-mirroring-for-git)
    - [Environment variables in environments](#environment-variables-in-environments)
    - [Better include functionality](#better-include-functionality)
- [New commands and options](#new-commands-and-options)
- [Notable refactors](#notable-refactors)
- [Documentation](#documentation)
- [Notable Bugfixes](#notable-bugfixes)
- [Additional deprecations, removals, and breaking changes](#additional-deprecations-removals-and-breaking-changes)
- [Spack community stats](#spack-community-stats)

## Stable Package API

In Spack `v1.0`, the package repository is separate from the Spack tool, giving you more control over the versioning of package recipes. There is also a stable [Package API](https://spack.readthedocs.io/en/latest/package_api.html) that is versioned separately from Spack.

This release of Spack supports package API from `v1.0` up to `v2.2`. The older `v1.0` package API is deprecated and may be removed in a future release, but we are guaranteeing that any Spack `v1.x` release will be backward compatible with Package API `v.2.x` -- i.e., it can execute code from the packages in *this* Spack release.

See the [Package API Documentation](https://spack.readthedocs.io/en/latest/package_api.html) for full details
on package versioning and compatibility. The high level details are:

  1. The `spack.package` Python module defines the Package API;
  2. The Package API *minor version* is incremented when new functions or classes are exported from `spack.package`; and
  3. The major version is incremented when functions or classes are removed or have breaking changes to their signatures (a rare occurrence).

This independent versioning allows package authors to utilize new Spack features without waiting for a new Spack release. Older Spack packages (API `v1.0`) may import code from outside of `spack.package`, e.g., from `spack.*` or `llnl.util.*`. This is deprecated and *not* included in the API guarantee. We will remove support for these packages in a future Spack release. 

### Separate Package Repository

The Spack `builtin` package repository no longer lives in the Spack git repository. You can find it here:

* https://github.com/spack/spack-packages

Spack clones the package repository automatically when you first run, so you do not have to manage this manually. By default, Spack version `v1.0` uses the `v2025.07`  release of `spack-packages`. You can find out more about it by looking at the [package releases](https://github.com/spack/spack-packages/releases).

Downloaded package repos are stored by default within `~/.spack`, but the fetch destination can be configured. (#50650). If you want your package repository to live somewhere else, run, e.g.:

```
spack repo set --destination ~/spack-packages builtin
```

You can also configure your *own* package repositories to be fetched automatically from git urls, just as you can with `builtin`. See the [repository configuration docs](https://spack.readthedocs.io/en/latest/repositories.html) for details.

### Updating and Pinning Packages

You can tell Spack to update the core package repository from a branch. For example, on `develop` or on a release, you can run commands like:

  ```shell
  # pull the latest packages
  spack repo update
  ```
or

  ```shell
  # check out a specific commit of the spack-packages repo
  spack repo update --commit 2bf4ab9585c8d483cc8581d65912703d3f020393 builtin
  ```

which will set up your configuration like this:

  ```yaml
  repos:
    builtin:
      git: "https://github.com/spack/spack-packages.git"
      commit: 2bf4ab9585c8d483cc8581d65912703d3f020393
  ```

You can use this within an environment to pin a specific version of its package files. See the [repository configuration docs](https://spack.readthedocs.io/en/latest/repositories.html) for more details (#50868, #50997, #51021).

### Breaking changes related to package repositories

1. The builtin repo now lives in `var/spack/repos/spack_repo/builtin` instead of `var/spack/repos/builtin`, and it has a new layout, which you can learn about in the [repo docs](https://spack.readthedocs.io/en/latest/repositories.html).

2. The module `spack.package` no longer exports the following symbols, mostly related to build systems: 
`AspellDictPackage`, `AutotoolsPackage`, `BundlePackage`, `CachedCMakePackage`, `cmake_cache_filepath`, `cmake_cache_option`, `cmake_cache_path`, `cmake_cache_string`, `CargoPackage`, `CMakePackage`, `generator`, `CompilerPackage`, `CudaPackage`, `Package`, `GNUMirrorPackage`, `GoPackage`, `IntelPackage`, `IntelOneApiLibraryPackageWithSdk`, `IntelOneApiLibraryPackage`, `IntelOneApiStaticLibraryList`, `IntelOneApiPackage`, `INTEL_MATH_LIBRARIES`, `LuaPackage`, `MakefilePackage`, `MavenPackage`, `MesonPackage`, `MSBuildPackage`, `NMakePackage`, `OctavePackage`, `PerlPackage`, `PythonExtension`, `PythonPackage`, `QMakePackage`, `RacketPackage`, `RPackage`, `ROCmPackage`, `RubyPackage`, `SConsPackage`, `SIPPackage`, `SourceforgePackage`, `SourcewarePackage`, `WafPackage`, `XorgPackage`

   These are now part of the `builtin` package repository, not part of core spack or its package API. When using repositories with package API `v2.0` and higher, *you must explicitly import these package classes* from the appropriate module in `spack_repo.builtin.build_systems` (see #50452 for more).

   e.g., for `CMakePackage`, you would write:

     ```python
     from spack_repo.builtin.build_systems.cmake import CMakePackage
     ```

   Note that `GenericBuilder` and `Package` *are* part of the core package API. They are currently re-exported from
   `spack_repo.builtin.build_systems.generic` for backward compatibility but may be removed from the package repo. You should prefer to import them from `spack.package`.

   The original names will still work for old-style (`v1.0`) package repositories but *not* in `v2.0` package repositories. Note that this means that the API stability promise does *not* include old-style package repositories. They are deprecated and will be removed in a future version. So, you should update as soon as you can.

3. Package directory names within `v2.0` repositories are now valid Python modules

    | Old                   | New                   | Description                         |
    |-----------------------|-----------------------|-------------------------------------|
    | `py-numpy/package.py` | `py_numpy/package.py` | hyphen is replaced by underscore.   |
    | `7zip/package.py`     | `_7zip/package.py`    | leading digits now preceded by _    |
    | `pass/package.py`     | `_pass/package.py`    | Python reserved words preceded by _ |


4. Spack has historically injected `import` statements into package recipes, so there was no need to use `from spack.package import *` (though we have included it in `builtin` packages for years. `from spack.package import *` (or more specific imports) will be necessary in packages. The magic we added in the early days of Spack was causing IDEs, code editors, and other tools not to be able to understand Spack packages. Now they use standard Python import semantics and should be compatible with modern Python tooling. This change was also necessary to support Python 3.13. (see #47947 for more details).

### Migrating to the new package API

Support will remain in place for the old repository layout for *at least a year*, so that you can continue to use old-style repos in conjunction with earlier versions. If you have custom repositories that need to migrate to the new layout, you can upgrade them to package API `v2.x` by running:

```
spack repo migrate
```

This will make the following changes to your repository:

   1. If you used to import from `spack.pkg.builtin` in Python, you now need to import from `spack_repo.builtin` instead:

       ```python
       # OLD: no longer supported
       from spack.pkg.builtin.my_pkg import MyPackage 

       # NEW: spack_repo is a Python namespace package
       from spack_repo.builtin.packages.my_pkg.package import MyPackage  
       ```
   2. Normalized directory names for packages
   3. New-style `spack.package` imports

See #50507, #50579, and #50594 for more.

## Compiler dependencies

Prior to `v1.0`, compilers in Spack were attributes on nodes in the spec graph, with a name and a version (e.g., `gcc@12.0.0`). In `v1.0` compilers are packages like any other package in Spack (see #45189). This means that they can have variants, targets, and other attributes that regular nodes have.

Here, we list the major changes that users should be aware of for this new model.

### Compiler configuration

In Spack `v1.0`, `compilers.yaml` is deprecated.  `compilers.yaml` is still read by Spack, if present. We will continue to support this for at least a year, but we may remove it after that. Users are encouraged to migrate their configuration to use `packages.yaml` instead. 

Old style `compilers.yaml` specification:

```yaml
compilers:
  - compiler:
      spec: gcc@12.3.1
      paths:
         c: /usr/bin/gcc
         cxx: /usr/bin/g++
         fc: /usr/bin/gfortran
       modules: [...]
```

New style `packages.yaml` compiler specification:

```yaml
packages:
  gcc:
    externals:
    - spec: gcc@12.3.1+binutils
      prefix: /usr
      extra_attributes:
        compilers:
          c: /usr/bin/gcc
          cxx: /usr/bin/g++
          fc: /usr/bin/gfortran
        modules: [...]
```

See [Configuring Compilers](https://spack.readthedocs.io/en/latest/configuring_compilers.html) for more details.


### Languages are virtual dependencies

Packages that need a C, C++, or Fortran compiler now **must** depend on `c`, `cxx`, or `fortran` as a build dependency, e.g.:

```python
class MyPackage(Package):
    depends_on("c", type="build")
    depends_on("cxx", type="build")
    depends_on("fortran", type="build")
```

Historically, Spack assumed that *every* package was compiled with C, C++, and Fortran. In Spack `v1.0`, we allow packages to simply not have a compiler if they do not need one. For example, pure Python packages would not depend on any of these, and you should not add these dependencies to packages that do not need them.

[Spack `v0.23`](https://github.com/spack/spack/releases/tag/v0.23.0) introduced language virtual dependencies, and we have back-ported them to `0.21.3` and `v0.22.2`.  In pre-1.0 Spack releases, these are a no-op. They are present so that language dependencies do not cause an error. This allows you to more easily use older Spack versions together with `v1.0`.

See #45217 for more details.

### The meaning of `%` has changed

In Spack `v0.x`, `%` specified a compiler with a name and an optional version. In Spack `v1.0`, it simply means "direct dependency". It is similar to the caret `^`, which means "direct *or* transitive dependency".

Unlike `^`, which specifies a dependency that needs to be unified for the whole graph, `%` can specify direct dependencies of particular nodes. This means you can use it to mix and match compilers, or `cmake` versions, or any other package for which *multiple* versions of the same build dependency are needed in the same graph. For example, in this spec:

```
foo ^hdf5 %cmake@3.1.2 ^zlib-ng %cmake@3.2.4
```

`hdf5` and `zlib-ng` are both transitive dependencies of `foo`, but `hdf5` will be built with `cmake@3.1.2` and `zlib-ng` will be built with `%cmake@3.2.4`. This is similar to mixing compilers, but you can now use `%` with other types of build dependencies, as well. You can have multiple versions of packages in the same graph, as long as they are purely build dependencies.

### Virtual assignment syntax

You can still specify compilers with `foo %gcc`, in which case `gcc` will be used to satisfy any `c`, `cxx`, and `fortran` dependencies of `foo`, but you can also be specific about the compiler that should be used for each language. To mix, e.g., `clang` and `gfortran`, you can now use *virtual assignment* like so:

```console
spack install foo %c,cxx=gcc %fortran=gfortran
```

This says to use `gcc` for `c` and `cxx`, and `gfortran` for `fortran`.
It is functionally equivalent to the already supported edge attribute syntax:

```
spack install foo %[virtuals=c,cxx] gcc %[virtuals=fortran] gfortran
```

But, virtual assignment is more legible. We use it as the default formatting for virtual edge attributes, and we print it in the output of `spack spec`, `spack find`, etc. For example:

```console
> spack spec zlib
 -   zlib@1.3.1+optimize+pic+shared build_system=makefile arch=darwin-sequoia-m1 %c,cxx=apple-clang@16.0.0
[e]      ^apple-clang@16.0.0 build_system=bundle arch=darwin-sequoia-m1
 -       ^compiler-wrapper@1.0 build_system=generic arch=darwin-sequoia-m1
[+]      ^gmake@4.4.1~guile build_system=generic arch=darwin-sequoia-m1 %c=apple-clang@16.0.0
[+]          ^compiler-wrapper@1.0 build_system=generic arch=darwin-sequoia-m1
```

You can see above that only `zlib` and `gmake` are compiled, and `gmake` uses only `c`. The other nodes are either external, and we cannot detect the compiler (`apple-clang`) or they are not compiled (`compiler-wrapper` is a shell script).

### Toolchains

Spack now has a concept of a "toolchain", which can be configured in `toolchains.yaml`. A toolchain is an alias for common dependencies, flags, and other spec properties that you can attach to a node in a graph with `%`.

Toolchains are versatile and composable as they are simply aliases for regular specs. You can use them to represent mixed compiler combinations, compiler/MPI/numerical library groups, particular runtime libraries, and flags -- all to be applied together. This allows you to do with compiler dependencies what we used to do with `compilers.yaml`, and more. 

Example mixed clang/gfortran toolchain:

```yaml
toolchains:
  clang_gfortran:
    - spec: %c=clang
      when: %c
    - spec: %cxx=clang
      when: %cxx
    - spec: %fortran=gcc
      when: %fortran
    - spec: cflags="-O3 -g"
    - spec: cxxflags="-O3 -g"
    - spec: fflags="-O3 -g"
```

This enables you to write `spack install foo %clang_gfortran`, and Spack will resolve the `%clang_gfortran` toolchain to include the dependencies and flags listed in `toolchains.yaml`.

You could also couple the intel compilers with `mvapich2` like so:

```yaml
toolchains:
  intel_mvapich2:
    - spec: %c=intel-oneapi-compilers @2025.1.1
      when: %c
    - spec: %cxx=intel-oneapi-compilers @2025.1.1
      when: %cxx
    - spec: %fortran=intel-oneapi-compilers @2025.1.1
      when: %fortran
    - spec: %mpi=mvapich2 @2.3.7-1 +cuda
      when: %mpi
```

The `when:` conditions here ensure that toolchain constraints are only applied when needed. See the [toolchains documentation](https://spack.readthedocs.io/en/latest/advanced_topics.html#defining-and-using-toolchains) or #50481 for details.

### Ordering of variants and compilers now matters

In Spack `v0.x`, these two specs parse the same:

```
pkg %gcc +foo
pkg +foo %gcc
```

The `+foo` variant applies to `pkg` in either case. In Spack `v1.0`, there is a breaking change, and `+foo` in `pkg %gcc +foo` now applies to `gcc`, since `gcc` is a normal package. This ensures we have the following symmetry:

```
pkg +foo %dep +bar  # `pkg +foo` depends on `dep +bar` directly
pkg +foo ^dep +bar  # `pkg +foo` depends on `dep +bar` directly or transitively
```

In Spack `v1.0` you may get errors at concretization time if `+foo` is not a variant of `gcc` in specs like`%pkg %gcc +foo`.

You can use the `spack style --spec-strings` command to update `package.py` files, `spack.yaml` files:

  ```shell
  # dry run
  spack style --spec-strings $(git ls-files)  # if you have a git repo
  spack style --spec-strings spack.yaml  # environments
  ```

  ```shell
  # use --fix to perform the changes listed by the dry run
  spack style --fix --spec-strings $(git ls-files)
  spack style --fix --spec-strings spack.yaml
  ```

  See #49808, #49438, #49439 for details.

## Additional Major Features

### Concurrent Package Builds

This release has completely reworked Spack's build scheduler, and it adds a `-p`/ `--concurrent-packages` argument to `spack install`, which can greatly accelerate builds with many packages. You can use it in combination with `spack install -j`. For example, this command:
   
```
spack install -p 4 -j 16
```
   
runs up to 4 package builds at once, each with up to 16 make jobs.  The default for `--concurrent-packages` is currently 1, so you must enable this feature yourself, either on the command line or by setting `config:concurrent_packages` (#50856):

```yaml
config:
  concurrent_packages: 1
```
   
As before, you can run `spack install` on multiple nodes in a cluster, if the filesystem where Spack's `install_tree` is located supports locking.

We will make concurrent package builds the default in `1.1`, when we plan to include support for `gmake`'s jobserver protocol and for line-synced output. Currently, setting `-p` higher than 1 can make Spack's output difficult to read.

### Content-addressed build caches

Spack `v1.0` changes the format of build caches to address a number of scaling and consistency issues with our old (aging) buildcache layout. The new buildcache format is content-addressed and enables us to make many operations atomic (and therefore safer). It is also more extensible than the old buildcache format and can enable features like split debug info and different signing methods in the future. See #48713 for more details.

Spack `v1.0` can still read, but not write to, the old build caches. The new build cache format is *not* backward compatible with the old format, *but* you can have a new build cache and an old build cache coexist beside each other. If you push to an old build cache, new binaries will start to show up in the new format.

You can migrate an old buildcache to the new format using the `spack buildcache migrate` command. It is nondestructive and can migrate an old build cache to a new one in-place. That is, it creates the new buildcache within the same directory, alongside the old buildcache.

As with other major changes, the old buildcache format is deprecated in `v1.0`, but will not be removed for at least a year.

### Better provenance and mirroring for git

Spack now resolves and preserves the commit of any git-based version at concretization time, storing the precise commit built on the Spec in a reserved `commit` variant.  This allows us to better reproduce git builds.    See #48702 for details.

Historically, Spack has only stored the ref name, e.g. the branch or tag, for git versions that did not already contain full commits. Now we can know exactly what was built regardless of how it was fetched.

As a consequence of this change, mirroring git repositories is also more robust. See #50604, #50906 for details.
  
### Environment variables in environments

You can now specify environment variables in your environment that should be set on activation (and unset on deactivation):

```yaml
spack:
  specs:
    - cmake%gcc
  env_vars:
    set:
      MY_FAVORITE_VARIABLE: "TRUE"
```
The syntax allows the same modifications that are allowed for modules: `set:`, `unset:`, `prepend_path:`, `append_path:`, etc.

See [the docs](https://spack.readthedocs.io/en/latest/env_vars_yaml.html or #47587 for more.

### Better include functionality

Spack allows you to include local or remote configuration files through `include.yaml`, and includes can be optional (i.e. include them only if they exist) or conditional (only include them under certain conditions:

```yaml
spack:
  include:
  - /path/to/a/required/config.yaml
  - path: /path/to/$os/$target/config
    optional: true
  - path: /path/to/os-specific/config-dir
    when: os == "ventura"
```

You can use this in an environment, or in an `include.yaml` in an existing configuration scope. Included configuration files are required *unless* they are explicitly optional or the entry's condition evaluates to `false`. Optional includes are specified with the `optional` clause and conditional ones with the ``when`` clause.

Conditionals use the same syntax as [spec list references](https://spack.readthedocs.io/en/latest/environments.html#spec-list-references) The [docs on `include.yaml`](https://spack.readthedocs.io/en/latest/include_yaml.html) have more information. You can also look at #48784.


## New commands and options
* `spack repo update` will pull the latest packages (#50868, #50997)
* `spack style --spec-strings` fixes old configuration file and packages (#49485)
* `spack repo migrate`: migrates old repositories to the new layout (#50507)
* `spack ci` no longer has a `--keep-stage` flag (#49467)
* The new `spack config scopes` subcommand will list active configuration scopes (#41455, #50703)
* `spack cd --repo <namespace>` (#50845)
* `spack location --repo <namespace>` (#50845)
* `--force` is now a common argument for all commands that do concretization (#48838)

## Notable refactors

* All of Spack is now in one top-level `spack` Python package
  * The `spack_installable` package is gone as it's no longer needed (#50996)
  * The top-level `llnl` package has been moved to `spack.llnl` and will likely be refactored more later (#50989)
  * Vendored dependencies that were previously in `_vendoring` are now in `spack.vendor` (#51005)
* Increased determinism when generating inputs for the ASP solver, leading to more consistent concretization results (#49471)
* Added fast, stable spec comparison, which also increases determinism of concretizer inputs, and more consistent results (#50625)
* Test deps are now part of the DAG hash, so builds with tests enabled will (correctly) have different hashes from builds without tests enabled (#48936)
* `spack spec` in an environment or on the command line will show unified output with the specs provided as roots (#47574)
* users can now set a timeout in `concretizer.yaml` in case they frequently hit long solves (#47661)
* GoPackage: respect `-j`` concurrency (#48421)
* We are using static analysis to speed up concretization (#48729)

## Documentation

We have overhauled a number of sections of the documentation. 
* The basics section of the documentation has been reorganized and updated (#50932)
* The [packaging guide](https://spack.readthedocs.io/en/latest/packaging_guide_creation.html) has been rewritten and broken into four separate, logically ordered sections (#50884).
* As mentioned above the entire [`spack.package` API](https://spack.readthedocs.io/en/latest/package_api.html) has been documented and consolidated to one package (#51010)

## Notable Bugfixes

* A race that would cause timeouts in certain parallel builds has been fixed. Every build now stages its own patches and cannot fight over them (causing a timeout) with other builds (#50697)
* The `command_line` scope is now *always* the top level. Previously environments could override command line settings (#48255)
* `setup-env.csh` is now hardened to avoid conflicts with user aliases (#49670)

## Additional deprecations, removals, and breaking changes
      
1. `spec["pkg"]` searches only direct dependencies and transitive link/run dependencies, ordered by depth. This avoids situations where we pick up unwanted deps of build/test deps. To reach those, you need to do `spec["build_dep"]["pkg"]` explicitly (#49016).

2. `spec["mpi"]` no longer works to refer to `spec` itself on specs like `openmpi` and `mpich` that could provide `mpi`. We only find `"mpi"` if it is provided by some dependency (see #48984).

3. We have removed some long-standing internal API methods on `spack.spec.Spec` so that we can decouple internal modules in the Spack code. `spack.spec` was including too many different parts of Spack.  
  * `Spec.concretize()` and `Spec.concretized()` have been removed. Use `spack.concretize.concretize_one(spec)` instead (#47971, #47978)
  * `Spec.is_virtual`` is now spack.repo.PATH.is_virtual (#48986)
  * `Spec.virtual_dependencies` has been removed (#49079)

4. #50603: Platform config scopes are now opt-in. If you want to use subdirectories like `darwin` or `linux` in your scopes, you'll need to include them explicitly in an `include.yaml` or in your `spack.yaml` file, like so:

    ```yaml
    include:
      - include: "${platform}"
        optional: true
    ```

5. #48488, #48502: buildcache entries created with Spack 0.19 and older using `spack buildcache create --rel` will no longer be relocated upon install. These old binaries should continue to work, except when they are installed with different `config:install_tree:projections` compared to what they were built with. Similarly, buildcache entries created with Spack 0.15 and older that contain long shebang lines wrapped with sbang will no longer be relocated.

6. #50462: the `package.py` globals `std_cmake_args`, `std_pip_args`, `std_meson_args` were removed. They were deprecated in Spack 0.23. Use `CMakeBuilder.std_args(pkg)`, `PythonPipBuilder.std_args(pkg)` and `MesonBuilder.std_args(pkg)` instead.

7. #50605, #50616: If you were using `update_external_dependencies()` in your private packages, note that it is going away in 1.0 to get it out of the package API. It is instead being moved into the concretizer, where it can change in the future, when we have a better way to deal with dependencies of externals, without breaking the package API.  We suspect that nobody was doing this, but it's technically a breaking change.

8. #48838: Two breaking command changes:
    * `spack install` no longer has a `-f` / `--file` option -- write `spack install ./path/to/spec.json` instead.
    * `spack mirror create` no longer has a short `-f` option -- use `spack mirror create --file` instead.

9. We no longer support the PGI compilers. They have been replaced by `nvhpc` (#47195)

10. Python 3.8 is deprecated in the Python package, as it is EOL (#46913)

11. The `target=fe` / `target=frontend` and `target=be` / `target=backend` targets from Spack's orignal compilation model for cross-compiled Cray and BlueGene systems are now deprecated (#47756)

## Spack community stats

* 2,276 commits updated package recipes
* 8,499 total packages, 214 new since v0.23.0
* 372 people contributed to this release
* 363 committers to packages
* 63 committers to core</small><a href='https://github.com/spack/spack/releases/tag/v1.0.0' target='_blank'>View Comment</a>