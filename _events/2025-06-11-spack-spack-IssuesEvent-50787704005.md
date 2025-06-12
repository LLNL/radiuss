---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/7997644?"
user: vbrunini
date: 2025-06-11
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/50879
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/vbrunini' target='_blank'>vbrunini</a> open issue <a href='https://github.com/spack/spack/issues/50879' target='_blank'>spack/spack#50879</a>.

<p>Improving composability of default package requirements</p><small>Currently any default package requirements specified via the `packages: all: require:` configuration are discarded for individual packages that have any requirements as described in the documentation ( https://spack.readthedocs.io/en/latest/packages_yaml.html#setting-default-requirements ). This makes it extremely error-prone (and IMO counterintuitive) to try and apply requirements across all packages in an environment, which is a common need particularly for variants like `target`, `cuda`, `cuda_arch`, `rocm`, `amdgpu_target`. For example consider an environment where you need to require `target=x86_64` for a build that works across a variety of machines, and also want to require specific versions of several packages....</small><a href='https://github.com/spack/spack/issues/50879' target='_blank'>View Comment</a>