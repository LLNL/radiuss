---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-02-12
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1335
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1335' target='_blank'>flux-framework/flux-sched#1335</a>.

<small>I'd have to dig a bit to be 100% sure but most of our traversals use some version of `for (auto edge : out_edges(g, vtx))`, looping over all edges going out of a given vertex.  The code before that change used explicit out edges for both edges to children and an edge to the parent. Once we switched to `bidirectional_graph` it no longer did that, `out_edges` would list only the downward edges or edges to other subsystems and `in_edges` would need to be included to go up.  As a side-effect, un-colored traversals would only go downward on tree-like graphs after that....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1335' target='_blank'>View Comment</a>