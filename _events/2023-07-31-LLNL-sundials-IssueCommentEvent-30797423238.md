---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2023-07-31
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/312
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/312' target='_blank'>LLNL/sundials#312</a>.

<small>The cause is that the SUNDIALS profiler uses MPI_WTime when SUNDIALS is built with MPI, but our serial examples do not initialize MPI. The error will go away if you set `SUNDIALS_BUILD_WITH_PROFILING=OFF`.  We will work on a fix. ...</small>

<a href='https://github.com/LLNL/sundials/issues/312' target='_blank'>View Comment</a>