---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/34784921?"
user: rchen20
date: 2024-08-06
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1690
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rchen20' target='_blank'>rchen20</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1690' target='_blank'>LLNL/RAJA#1690</a>.

<small>After some discussion with @MrBurmark, we've both concluded that the GPU backends for a valloc interface have enough complications that will require a re-design of valloc. The problem lies in the fact that the GPU backend implementation of `grid_reduce` (e.g. policy/cuda/reduce.hpp) relies on the reduction object and the val-x type (T). In the current valloc design, the val-x type can become a complex type (ValLoc, ValOp, ValOp<ValLoc>), which was not the intended use for `grid_reduce` which primarily should handle basic data types. To remedy this, I will change the valloc interface requirements, and attempt to hide the various val-x types within RAJA, rather than exposing them to the user. Here is an example of the new valloc we have in mind:...</small>

<a href='https://github.com/LLNL/RAJA/pull/1690' target='_blank'>View Comment</a>