---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7450069?"
user: marcosvanella
date: 2024-10-08
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1129
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/marcosvanella' target='_blank'>marcosvanella</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1129' target='_blank'>hypre-space/hypre#1129</a>.

<small>Hi Victor I'll try your suggestion. We have added HYPRE PCG_AMG support for one of our Poisson Solvers (A local solver that works by mesh block and single MPI process, tied within a block Jacobi iteration), we are getting our CI workflow prepared to be able to choose between PARDISO and HYPRE as base solvers. Once we have our verification cases up and running with HYPRE and our local solver, we will add HYPRE to our global matrix solver across all MPI processes in a calculation (currently uses CLUSTER_SPARSE_SOLVER from MKL). The plan is to have these options for users in an upcoming release, which will be also of use for ARM Macs users (they can't compile with MKL so we plan to have HYPRE as their option)....</small>

<a href='https://github.com/hypre-space/hypre/issues/1129' target='_blank'>View Comment</a>