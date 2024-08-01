---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-07-31
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6166
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6166' target='_blank'>flux-framework/flux-core#6166</a>.

<small>Yeah, unfortunately I think I have an idea of the issue here and it is probably a slight design flaw in the way `flux resource list` works. An empty resource set is used as a placeholder when there are no nodes in a given state. An empty resource set obviously has no associated queue. This goes back to when Flux didn't even yet support queues....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6166' target='_blank'>View Comment</a>