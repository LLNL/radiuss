---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/9196588?"
user: termi-official
date: 2022-07-14
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/2852
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/termi-official' target='_blank'>termi-official</a> commented on issue <a href='https://github.com/mfem/mfem/issues/2852' target='_blank'>mfem/mfem#2852</a>.

<small>I am getting rather confident that the blocks which I see in the measurements come from some kind of interaction with the omp instrumentation, because building everything without caliper does not have the same issue. There still remains a performance gap between pure mpi and pure omp for pure partial assembly+cg performance for the diffusion problem as set up in ex1. The omp device ("serial problem as in ex1) is 40-50% slower than mpi ("parallel problem as in ex1p), because the CPU utilization never really peaks - which I think can be attributed to having a not optimized implementation of the opm code. ...</small>

<a href='https://github.com/mfem/mfem/issues/2852' target='_blank'>View Comment</a>