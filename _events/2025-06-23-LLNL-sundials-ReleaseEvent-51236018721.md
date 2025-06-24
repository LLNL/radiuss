---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2025-06-23
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/releases/tag/v7.4.0
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> released <a href='https://github.com/LLNL/sundials/releases/tag/v7.4.0' target='_blank'>v7.4.0</a>.

<small>### New Features and Enhancements

`ARKodeSetCFLFraction` now allows `cfl_frac` to be greater than or equal to one.

Added an option to enable compensated summation of the time accumulator for all of ARKODE. This was previously only an option for the SPRKStep module. The new function to call to enable this is `ARKodeSetUseCompensatedSums`.

### Bug Fixes

Fixed segfaults in `CVodeAdjInit` and `IDAAdjInit` when called after adjoint memory has been freed.

Fixed a CMake bug that would cause the Caliper compile test to fail at configure time.

Fixed a bug in the CVODE/CVODES `CVodeSetEtaFixedStepBounds` function which disallowed setting `eta_min_fx` or `eta_max_fx` to 1.

`SUNAdjointStepper_PrintAllStats` was reporting the wrong quantity for the number of "recompute passes" and has been fixed.

### Deprecation Notices

The `SPRKStepSetUseCompensatedSums` function has been deprecated. Use the `ARKodeSetUseCompensatedSums` function instead.</small><a href='https://github.com/LLNL/sundials/releases/tag/v7.4.0' target='_blank'>View Comment</a>