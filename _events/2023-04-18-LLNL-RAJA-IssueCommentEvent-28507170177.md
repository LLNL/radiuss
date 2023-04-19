---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/34784921?"
user: rchen20
date: 2023-04-18
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1462
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rchen20' target='_blank'>rchen20</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1462' target='_blank'>LLNL/RAJA#1462</a>.

<small>This behavior is exactly what `RAJA::expt::scalar_register` is expected to do: load the first value of the array into the VectorRegister, due to being a scalar. At the time, we were using `scalar_register` on a BlueOS system, when we should have tried a `cuda_warp_register`. The more typical usage is on a TOSS system with one of the AVX register types, which operates correctly loading all elements of the array into the vector register....</small>

<a href='https://github.com/LLNL/RAJA/issues/1462' target='_blank'>View Comment</a>