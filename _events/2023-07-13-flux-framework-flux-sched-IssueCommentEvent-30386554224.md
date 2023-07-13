---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-07-13
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1041
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1041' target='_blank'>flux-framework/flux-sched#1041</a>.

<small>Right, the other thing I didn’t mention was I think either way we should be using a bidirectional graph so the in edge is an in edge rather than an out edge. I  hadn’t seen the multi-edge code for pool resources though, that will need some thought for sure. The simplest option would be splitting the vertices, but that sounds awful. We do need a way to handle oversubscription too though, and that’s basically the same problem, so if we come up with a way to allocate part of a vertex that should cover pool resources as well....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1041' target='_blank'>View Comment</a>