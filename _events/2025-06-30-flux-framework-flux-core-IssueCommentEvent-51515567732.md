---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-06-30
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6704
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6704' target='_blank'>flux-framework/flux-core#6704</a>.

<small>That sounds right, we could probably get away with a `replace` op for this one. Maybe allow updates to `job.update.<json-patch-path-root>` so you could do (I forget the exact path, but something like) `job.update./attributes/dependencies` to allow updates to it. Depending on how granular we want the control to be that might not be quite right but it would make it easy to allow updates to specific roots of the jobspec, or even restrict it to specific array members if we ever needed to....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6704' target='_blank'>View Comment</a>