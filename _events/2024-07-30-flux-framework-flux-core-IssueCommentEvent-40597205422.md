---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-07-30
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6157
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6157' target='_blank'>flux-framework/flux-core#6157</a>.

<small>I agree in general that we want plugin-provided options, and documenting setattr targets would be fantastic, but at the same time banks are pretty deeply baked into most people's notion of what a resource manager does.  Enough so that I'm honestly wondering if it's worth just always having the option, and having there be a logical bank, "default" or something, even when we're running without accounting.  Most of the system need not care, but it would mean we could provide better failure modes if someone specifies the flag _and there's nothing that can do anything about it_.  Having it do nothing silently is only a minor issue when there's no accounting plugin, you probably just don't care, but `--setattr=system.banc=aalsdhf` being silently ignored is substantially less ideal.  Honestly I think that would be the biggest win is if we could make it so we can tell people when, under some conditions, they've set an attribute that can't possibly be right.  Maybe just for attributes under `system.` or something but still....</small>

<a href='https://github.com/flux-framework/flux-core/pull/6157' target='_blank'>View Comment</a>