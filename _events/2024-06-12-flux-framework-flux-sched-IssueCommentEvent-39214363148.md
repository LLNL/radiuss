---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2024-06-12
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1222
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>flux-framework/flux-sched#1222</a>.

<small>The following script reproduces an approximately linear scheduling slowdown as a function of the number of jobs submitted and then cancelled with a constraint specifying a single node. For example, it takes 10 4-node jobs without constraints running `hostname` 113s to complete with 500 jobs with constraints submitted then cancelled. For 1000 submitted and cancelled jobs the 4-node jobs take 248s to complete. I ran tests with up to 5000 submitted and cancelled jobs....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>View Comment</a>