---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2024-10-21
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1292
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1292' target='_blank'>flux-framework/flux-sched#1292</a>.

<small>I realized the brokerless resource cancellation implemented in this PR currently will lead to highly undesirable behavior. All the brokerless vertices will get cancelled in the first partial cancel traversal. That means that they will be allocatable before the final `.free` which can lead to state inconsistency between sched and core....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1292' target='_blank'>View Comment</a>