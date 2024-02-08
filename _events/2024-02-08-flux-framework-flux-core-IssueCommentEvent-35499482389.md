---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2024-02-08
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4417
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4417' target='_blank'>flux-framework/flux-core#4417</a>.

<small>@grondo I'm resurrecting this old issue for some SCR work. In a nested instance, it looks like if I simulate a node failure by killing one of the non-critical brokers, the parent's doom plugin kicks in after a timeout. If I create the nested instance with `-oexit-timeout=none` (e.g. `flux alloc -N3 -oexit-timeout=none`) then the doom plugin doesn't kick in and the instance survives. So I was initially thinking that, in order to tolerate non-critical node failures, users would need to add the `-oexit-timeout=none` option. But I'm guessing that in the event of a real node failure, the parent instance wouldn't trigger the doom plugin at all, because it would see a lost rank of its own rather than a task that failed on an otherwise working node?...</small>

<a href='https://github.com/flux-framework/flux-core/issues/4417' target='_blank'>View Comment</a>