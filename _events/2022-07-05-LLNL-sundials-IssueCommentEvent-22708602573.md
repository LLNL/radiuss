---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2022-07-05
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/171
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/171' target='_blank'>LLNL/sundials#171</a>.

<small>There is no point-to-point communication within SUNDIALS itself, only reductions to a scalar on the CPU (e.g., for norms) so no GPU aware MPI is needed for this.  The point-to-point communication would only take place only in the user-supplied callbacks or possibly in external libraries for the linear solve (such as SuperLU_DIST). The obvious example of a user-supplied function is the right-hand-side function.  It is up to you how the GPU buffers are handled in this function....</small>

<a href='https://github.com/LLNL/sundials/issues/171' target='_blank'>View Comment</a>