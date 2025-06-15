---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2025-06-14
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6873
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6873' target='_blank'>flux-framework/flux-core#6873</a>.

<small>This is pretty neat. However it seems like its usefulness will be limited as long as the result of the proxy job is always reported as failure. I see why a fatal exception was used to get the job from DEPEND to CLEANUP state in the prototype, since there's no other way to do that currently, but I wonder if we can think up a better way that allows the proxy job result to reflect the result of the actual job.  That way workflow tools, not to mention Flux native dependency schemes like `afterok` ,would not need to treat delegated jobs specially when they need to fetch the job result....</small>

<a href='https://github.com/flux-framework/flux-core/pull/6873' target='_blank'>View Comment</a>