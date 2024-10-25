---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2024-10-24
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1292
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1292' target='_blank'>flux-framework/flux-sched#1292</a>.

<small>I was able to implement propagating the free state to the traverser. I ran performance comparisons between the two approaches (propagation vs unconditional full cleanup cancel) and observed that the unconditional full cleanup cancel is almost always faster than propagating the free state. The exception appears to be when processing more than 1 `free` RPC....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1292' target='_blank'>View Comment</a>