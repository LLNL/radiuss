---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/34784921?"
user: rchen20
date: 2024-03-08
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1595
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rchen20' target='_blank'>rchen20</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1595' target='_blank'>LLNL/RAJA#1595</a>.

<small>After trying again with the latest RAJA/develop, I'm getting the same error linkage specification error as before, with the `-fopenmp-version=45` being a successful hack to get around this. I think Tom is correct in that perhaps nvcc and clang disagree on how `omp_is_initial_device` is decorated with `inline` in their respective versions of the headers....</small>

<a href='https://github.com/LLNL/RAJA/issues/1595' target='_blank'>View Comment</a>