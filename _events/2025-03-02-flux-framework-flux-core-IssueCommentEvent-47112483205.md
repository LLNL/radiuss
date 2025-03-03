---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-03-02
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6667
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6667' target='_blank'>flux-framework/flux-core#6667</a>.

<small>That's really good to know. If we go with the property approach, that should be pretty trivial (as would arbitrary other ones) if we plan it as a more general mechanism.  Our label implementation is a generic string=>string map, and we can do matches on labels and their values, so that would be a pretty good way to start (I could see reasons not to do it that way longer term but I think it would get us pretty far). Maybe we could add something to jobspec or in the generic attributes for "ephemeral labels" that are associated with a job and apply to a resource or the node?  Then it's just two additions to fluxion:...</small>

<a href='https://github.com/flux-framework/flux-core/issues/6667' target='_blank'>View Comment</a>