---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2024-04-20
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1176
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1176' target='_blank'>flux-framework/flux-sched#1176</a>.

<small>I fixed a case in `find_vertex` where the uninitialized `vtx` was getting returned when not found in the graph. Since an uninitialized `vtx_t` `!= boost::graph_traits<resource_graph_t>::null_vertex ()` that caused the check to identify duplicate vertices when initializing the graph....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1176' target='_blank'>View Comment</a>