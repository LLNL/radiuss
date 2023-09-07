---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2023-09-07
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/releases/tag/v6.6.1
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> released <a href='https://github.com/LLNL/sundials/releases/tag/v6.6.1' target='_blank'>v6.6.1</a>.

<small>Updated the Tpetra NVector interface to support Trilinos 14.

Fixed a memory leak when destroying a CUDA, HIP, SYCL, or system SUNMemoryHelper object.

Fixed a bug in ARKODE, CVODE, CVODES, IDA, and IDAS where the stop time may not be cleared when using normal mode if the requested output time is the same as the stop time. Additionally, with ARKODE, CVODE, and CVODES an unnecessary interpolation of the solution at the stop time may occur in this case.</small><a href='https://github.com/LLNL/sundials/releases/tag/v6.6.1' target='_blank'>View Comment</a>