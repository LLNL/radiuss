---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12800412?"
user: rhornung67
date: 2022-11-03
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1368
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rhornung67' target='_blank'>rhornung67</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1368' target='_blank'>LLNL/RAJA#1368</a>.

<small>@chichunchen do you need to use the OpenMP target offload back-end for RAJA? We don't consider it production ready, rather something we try to maintain it to test compilers and we don't spend much time on it. Depending on what you are trying to do and what hardware you are targeting, you will have better luck with performance, compiler and RAJA support with the CUDA or HIP back-ends. The RAJA SYCL back-end is in development, but a large fraction of features are supported already....</small>

<a href='https://github.com/LLNL/RAJA/issues/1368' target='_blank'>View Comment</a>