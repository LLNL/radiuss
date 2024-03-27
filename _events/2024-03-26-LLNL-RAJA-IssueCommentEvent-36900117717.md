---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/34784921?"
user: rchen20
date: 2024-03-26
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1485
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rchen20' target='_blank'>rchen20</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1485' target='_blank'>LLNL/RAJA#1485</a>.

<small>Apart from the Intel compiler inaccuracies, there is definitely something wrong with `test-tensor-matrix-*-ColMajor-ET_Subtract`. When built with `clang/14.0.6-magic`, it looks like the tail of the vectorized computation is not being properly computed, and possibly is optimized out by the compiler in `-O3` (works properly with `-O0`, like with Intel). I'm looking further in to the cause....</small>

<a href='https://github.com/LLNL/RAJA/issues/1485' target='_blank'>View Comment</a>