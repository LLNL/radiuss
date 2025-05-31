---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2025-05-29
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6842
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6842' target='_blank'>flux-framework/flux-core#6842</a>.

<small>> After typing that up, I realized one issue with a special exit code is that exiting early from the prolog due to a potentially nonfatal error is probably not a good idea. This could skip other parts of the prolog that are necessary for preparing a node for use by the user. The node may be drained, but the user could still log in, or choose to undrain the node....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6842' target='_blank'>View Comment</a>