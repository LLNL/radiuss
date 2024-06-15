---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6393677?"
user: adayton1
date: 2024-06-15
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1672
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/adayton1' target='_blank'>adayton1</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1672' target='_blank'>LLNL/RAJA#1672</a>.

<small>@MrBurmark, would you be willing to look at the changes to hip atomics? The previous implementation of atomicCAS relied on volatile, so I changed the implementation to use an atomic load. To avoid a circular dependency, I've changed in the implementation of atomicLoad to use the intrinsic if available, otherwise I fall back to atomicOr(address, 0). Does that make sense, or would it be better to fall back to atomicCAS(address, 0, 0) or something else? I think atomicOr will be better than atomicAdd, but I'm not sure if atomicCAS can avoid the write in some cases. I also modified atomicExchange to use reinterpret casting instead of atomicCAS in a loop, then made atomicStore use atomicExchange if the intrinsic is not available....</small>

<a href='https://github.com/LLNL/RAJA/pull/1672' target='_blank'>View Comment</a>