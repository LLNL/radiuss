---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-09-01
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4533
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4533' target='_blank'>flux-framework/flux-core#4533</a>.

<small>I can't remember entirely how our `per-resource` support is currently implemented, but jobspec V1 includes support for `per_slot` in `count` rather than `total`, so we could construct a `nodes[count]>slot` resource spec and then use `count:per_slot:tasks_per_node` to get there.  We could probably also do the math locally as long as we require the number of nodes to be explicit, and only allow exclusive nodes with that option, then `count:total:count * tasks_per_node` should do it....</small>

<a href='https://github.com/flux-framework/flux-core/issues/4533' target='_blank'>View Comment</a>