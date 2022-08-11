---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2022-08-10
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/releases/tag/v6.3.0
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> released <a href='https://github.com/LLNL/sundials/releases/tag/v6.3.0' target='_blank'>v6.3.0</a>.

<small>Added GetUserData functions in each package to retrieve the user data pointer provided to SetUserData functions. See ARKStepGetUserData, ERKStepGetUserData, MRIStepGetUserData, CVodeGetUserData, IDAGetUserData, or KINGetUserData for more information.

Fixed a bug in ERKStepReset, ERKStepReInit, ARKStepReset, ARKStepReInit, MRIStepReset, and MRIStepReInit where a previously-set value of tstop (from a call to ERKStepSetStopTime, ARKStepSetStopTime, or MRIStepSetStopTime, respectively) would not be cleared.

Updated MRIStepReset to call the corresponding MRIStepInnerResetFn with the same (tR,yR) arguments for the MRIStepInnerStepper object that is used to evolve the MRI "fast" time scale subproblems.

Added a new [example](https://github.com/LLNL/sundials/blob/main/examples/cvode/serial/cvRocket_dns.c) which demonstrates using CVODE with a discontinuous right-hand-side function and rootfinding.

Added a variety of embedded DIRK methods from [Kennedy & Carpenter, NASA TM-2016-219173, 2016] and [Kennedy & Carpenter, Appl. Numer. Math., 146, 2019] to ARKODE.

Fixed the unituitive behavior of the USE_GENERIC_MATH CMake option which caused the double precision math functions to be used regardless of the value of SUNDIALS_PRECISION. Now, SUNDIALS will use precision appropriate math functions when they are available and the user may provide the math library to link to via the advanced CMake option SUNDIALS_MATH_LIBRARY.

Changed SUNDIALS_LOGGING_ENABLE_MPI CMake option default to be 'OFF'.</small><a href='https://github.com/LLNL/sundials/releases/tag/v6.3.0' target='_blank'>View Comment</a>