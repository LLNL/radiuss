---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4537104?"
user: artv3
date: 2025-05-11
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1843
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/artv3' target='_blank'>artv3</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1843' target='_blank'>LLNL/RAJA#1843</a>.

<small>Albeit I haven't been able to generate the assembly/PTX code per @rchen20's request. It does seem that the discussion recognizes that pragma unroll does nothing whenever nvcc is enabled for both host and device code. Thus the proposition here is remove loop unrolling whenever nvcc is used since it is ignored anyway. I think that is reasonable to me, it could be the case that the pragma is supported later on but perhaps we can revisit and  reimplement the pragma.  Aside from no warnings I also believe that our code performance will remain the same. ...</small>

<a href='https://github.com/LLNL/RAJA/pull/1843' target='_blank'>View Comment</a>