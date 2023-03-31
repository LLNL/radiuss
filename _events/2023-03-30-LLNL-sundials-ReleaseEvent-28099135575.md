---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2023-03-30
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/releases/tag/v6.5.1
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> released <a href='https://github.com/LLNL/sundials/releases/tag/v6.5.1' target='_blank'>v6.5.1</a>.

<small>Added the functions `ARKStepClearStopTime`, `ERKStepClearStopTime`, `MRIStepClearStopTime`, `CVodeClearStopTime`, and `IDAClearStopTime` to disable a previously set stop time.

The default interpolant in ARKODE when using a first order method has been updated to a linear interpolant to ensure values obtained by the integrator are returned at the ends of the time interval. To restore the previous behavior of using a constant interpolant call `ARKStepSetInterpolantDegree`, `ERKStepSetInterpolantDegree`, or `MRIStepSetInterpolantDegree` and set the interpolant degree to zero before evolving the problem.

Fixed build errors when using SuperLU_DIST with ROCM enabled to target AMD GPUs.

Fixed compilation errors in some SYCL examples when using the `icx` compiler.</small><a href='https://github.com/LLNL/sundials/releases/tag/v6.5.1' target='_blank'>View Comment</a>