---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2023-03-08
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4986
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4986' target='_blank'>flux-framework/flux-core#4986</a>.

<small>This seems a reasonable request. Even if most of the time you do want to keep the original timestamp to avoid loss of information, I think we would still want to provide a way to "atomically" re-drain a node, e.g. when one issue is resolved, but the node is being drained for another reason. Currently you'd have to undrain then redrain the node, at which time the scheduler might allocate a job to that resource....</small>

<a href='https://github.com/flux-framework/flux-core/issues/4986' target='_blank'>View Comment</a>