---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2022-07-08
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4325
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4325' target='_blank'>flux-framework/flux-core#4325</a>.

<small>I don't have any further suggestions. I would try whether something like `[jsrun ...] flux start flux mini run -ompi=spectrum -N1 -n4 -g0 exaconstit-mechanics-v0_6_1 -opt options.toml` works though. If so then I would try `[jsrun ...] flux start flux mini alloc -N1 -n1 -c40 flux mini run -ompi=spectrum -N1 -n4 -g0 exaconstit-mechanics-v0_6_1 -opt options.toml` (I'm just trying to progressively get closer to what your script is doing)....</small>

<a href='https://github.com/flux-framework/flux-core/issues/4325' target='_blank'>View Comment</a>