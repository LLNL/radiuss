---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2024-02-29
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/releases/tag/v7.0.0
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> released <a href='https://github.com/LLNL/sundials/releases/tag/v7.0.0' target='_blank'>v7.0.0</a>.

<small>### Major Feature

SUNDIALS now has more robust and uniform error handling. Non-release builds will be built with additional error checking by default. See the [Error Checking](https://sundials.readthedocs.io/en/latest/sundials/Errors_link.html) section in the user guide for details.

### Breaking Changes

#### Minimum C Standard

SUNDIALS now requires using a compiler that supports a subset of the C99 standard. Note with the Microsoft C/C++ compiler the subset of C99 features utilized by SUNDIALS are available starting with [Visual Studio 2015](https://learn.microsoft.com/en-us/cpp/overview/visual-cpp-language-conformance?view=msvc-170#c-standard-library-features-1).

#### Deprecated Types and Functions Removed

The previously deprecated types `realtype` and `booleantype` were removed from `sundials_types.h` and replaced with `sunrealtype` and `sunbooleantype`. The deprecated names for these types can be used by including the header file `sundials_types_deprecated.h` but will be fully removed in the next major release. Functions, types and header files that were previously deprecated have also been removed.

#### Error Handling Changes

With the addition of the new error handling capability, the `*SetErrHandlerFn` and `*SetErrFile` functions in CVODE(S), IDA(S), ARKODE, and KINSOL have been removed. Users of these functions can use the functions `SUNContext_PushErrHandler`, and `SUNLogger_SetErrorFilename` instead. For further details see the [Error Checking](https://sundials.readthedocs.io/en/latest/sundials/Errors_link.html) and [Logging](https://sundials.readthedocs.io/en/latest/sundials/Logging_link.html) sections in the documentation.

In addition the following names/symbols were replaced by ``SUN_ERR_*`` codes:

| Removed                                                    | Replaced with ``SUNErrCode``         |
|:--------------------------------------------------------|:------------------------------------------------|
| `SUNLS_SUCCESS`                                  | `SUN_SUCCESS`                             |
| `SUNLS_UNRECOV_FAILURE`                 | no replacement (value was unused) |
| `SUNLS_MEM_NULL`                                | `SUN_ERR_ARG_CORRUPT`         |
| `SUNLS_ILL_INPUT`                                  | `SUN_ERR_ARG_*`                         |
| `SUNLS_MEM_FAIL`                                  | `SUN_ERR_MEM_FAIL`                  |
| `SUNLS_PACKAGE_FAIL_UNREC`           | `SUN_ERR_EXT_FAIL`                   |
| `SUNLS_VECTOROP_ERR`                      | `SUN_ERR_OP_FAIL`                     |
| `SUN_NLS_SUCCESS`                              | `SUN_SUCCESS`                            |
| `SUN_NLS_MEM_NULL`                            | `SUN_ERR_ARG_CORRUPT`        |
| `SUN_NLS_MEM_FAIL`                              | `SUN_ERR_MEM_FAIL`                 |
| `SUN_NLS_ILL_INPUT`                              | `SUN_ERR_ARG_*`                        |
| `SUN_NLS_VECTOROP_ERR`                  | `SUN_ERR_OP_FAIL`                     |
| `SUN_NLS_EXT_FAIL`                               | `SUN_ERR_EXT_FAIL`                   |
| `SUNMAT_SUCCESS`                                | `SUN_SUCCESS`                           |
| `SUNMAT_ILL_INPUT`                                | `SUN_ERR_ARG_*`                       |
| `SUNMAT_MEM_FAIL`                                | `SUN_ERR_MEM_FAIL`                |
| `SUNMAT_OPERATION_FAIL`                    | `SUN_ERR_OP_FAIL`                   |
| `SUNMAT_MATVEC_SETUP_REQUIRED` | `SUN_ERR_OP_FAIL`                   |

The following functions have had their signature updated to ensure they can leverage the new SUNDIALS error handling capabilities.

```c
// From sundials_futils.h
SUNDIALSFileOpen
SUNDIALSFileClose

// From sundials_memory.h
SUNMemorNewEmpty
SUNMemoryHelper_Alias
SUNMemoryHelper_Wrap

// From sundials_nvector.h
N_VNewVectorArray
```

#### SUNComm Type Added

We have replaced the use of a type-erased (i.e., `void*`) pointer to a communicator in place of `MPI_Comm` throughout the SUNDIALS API with a `SUNComm`, which is just a typedef to an `int` in builds without MPI and a typedef to a `MPI_Comm` in builds with MPI. As a result:

- All users will need to update their codes because the call to  `SUNContext_Create` now takes a `SUNComm` instead  of type-erased pointer to a communicator. For non-MPI codes,  pass `SUN_COMM_NULL` to the `comm` argument instead of  `NULL`. For MPI codes, pass the `MPI_Comm` directly.

- The same change must be made for calls to `SUNLogger_Create` or `SUNProfiler_Create`.

- Some users will need to update their calls to `N_VGetCommunicator`, and update any custom `N_Vector` implementations that provide `N_VGetCommunicator`, since it now returns a `SUNComm`.

The change away from type-erased pointers for `SUNComm` fixes problems like the one described in [GitHub Issue #275](https://github.com/LLNL/sundials/issues/275).

The SUNLogger is now always MPI-aware if MPI is enabled in SUNDIALS and the `SUNDIALS_LOGGING_ENABLE_MPI` CMake option and macro definition were removed accordingly.

#### SUNDIALS Core Library

Users now need to link to `sundials_core` in addition to the libraries already linked to. This will be picked up automatically in projects that use the SUNDIALS CMake target. The library `sundials_generic` has been superseded by `sundials_core` and is no longer available. This fixes some duplicate symbol errors on Windows when linking to multiple SUNDIALS libraries.

#### Fortran Interface Modules Streamlined

We have streamlined the Fortran modules that need to be included by users by combining the SUNDIALS core into one Fortran module, `fsundials_core_mod`. Modules for implementations of the core APIs still exist (e.g., for the Dense linear solver there is `fsunlinsol_dense_mod`) as do the modules for the SUNDIALS packages (e.g., `fcvode_mod`). The following modules are the ones that have been consolidated into `fsundials_core_mod`:

```
fsundials_adaptcontroller_mod
fsundials_context_mod
fsundials_futils_mod
fsundials_linearsolver_mod
fsundials_logger_mod
fsundials_matrix_mod
fsundials_nonlinearsolver_mod
fsundials_nvector_mod
fsundials_profiler_mod
fsundials_types_mod
```

### Deprecation notice

The functions in `sundials_math.h` will be deprecated in the next release.

```c
  sunrealtype SUNRpowerI(sunrealtype base, int exponent);
  sunrealtype SUNRpowerR(sunrealtype base, sunrealtype exponent);
  sunbooleantype SUNRCompare(sunrealtype a, sunrealtype b);
  sunbooleantype SUNRCompareTol(sunrealtype a, sunrealtype b, sunrealtype tol);
  sunrealtype SUNStrToReal(const char* str);
```

Additionally, the following header files (and everything in them) will be
deprecated -- users who rely on these are recommended to transition to the
corresponding `SUNMatrix` and `SUNLinearSolver` modules:

```c
sundials_direct.h
sundials_dense.h
sundials_band.h
```

### Minor Changes

Fixed [#329](https://github.com/LLNL/sundials/issues/329) so that C++20 aggregate initialization can be used.

Fixed integer overflow in the internal SUNDIALS hashmap. This resolves [#409](https://github.com/LLNL/sundials/issues/409) and [#249](https://github.com/LLNL/sundials/issues/249).

The `CMAKE_BUILD_TYPE` defaults to `RelWithDebInfo` mode now i.e., SUNDIALS will be built with optimizations and debugging symbols enabled by default. Previously the build type was unset by default so no optimization or debugging flags were set.

The advanced CMake options to override the inferred LAPACK name-mangling scheme have been updated from `SUNDIALS_F77_FUNC_CASE` and `SUNDIALS_F77_FUNC_UNDERSCORES` to `SUNDIALS_LAPACK_CASE` and `SUNDIALS_LAPACK_UNDERSCORES`, respectively.

Converted most previous Fortran 77 and 90 examples to use SUNDIALS' Fortran 2003 interface.</small><a href='https://github.com/LLNL/sundials/releases/tag/v7.0.0' target='_blank'>View Comment</a>