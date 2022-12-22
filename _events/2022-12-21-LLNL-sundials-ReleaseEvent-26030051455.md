---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2022-12-21
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/releases/tag/v6.5.0
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> released <a href='https://github.com/LLNL/sundials/releases/tag/v6.5.0' target='_blank'>v6.5.0</a>.

<small>A new capability to keep track of memory allocations made through the `SUNMemoryHelper` classes has been added. Memory allocation stats can be accessed through the `SUNMemoryHelper_GetAllocStats` function. See the documentation for the `SUNMemoryHelper` classes for more details.

Added the functions `ARKStepGetJac`, `ARKStepGetJacTime`, `ARKStepGetJacNumSteps`, `MRIStepGetJac`, `MRIStepGetJacTime`, `MRIStepGetJacNumSteps`, `CVodeGetJac`, `CVodeGetJacTime`, `CVodeGetJacNumSteps`, `IDAGetJac`, `IDAGetJacCj`, `IDAGetJacTime`, `IDAGetJacNumSteps`, `KINGetJac`, `KINGetJacNumIters` to assist in debugging simulations utilizing a matrix-based linear solver.

Added support for CUDA 12.

Added support for the SYCL backend with RAJA 2022.x.y.

Fixed an underflow bug during root finding in ARKODE, CVODE, CVODES, IDA and IDAS.

Fixed an issue with finding oneMKL when using the `icpx` compiler with the `-fsycl` flag as the C++ compiler instead of `dpcpp`.

Fixed the shape of the arrays returned by `FN_VGetArrayPointer` functions as well as the `FSUNDenseMatrix_Data`, `FSUNBandMatrix_Data`, `FSUNSparseMatrix_Data`, `FSUNSparseMatrix_IndexValues`, and `FSUNSparseMatrix_IndexPointers` functions. Compiling and running code that uses the SUNDIALS Fortran interfaces with bounds checking will now work.

Fixed an implicit conversion error in the Butcher table for ESDIRK5(4)7L[2]SA2.</small><a href='https://github.com/LLNL/sundials/releases/tag/v6.5.0' target='_blank'>View Comment</a>