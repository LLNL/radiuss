---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2024-02-18
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1137
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1137' target='_blank'>flux-framework/flux-sched#1137</a>.

<small>After further thought, a much better way to get the allocated state is just to query the root `planner_multi`. This completely avoids a traversal of the resource graph and scales very well. Here are the timings for using a `planner_multi` query in place of a `find` traversal:...</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1137' target='_blank'>View Comment</a>