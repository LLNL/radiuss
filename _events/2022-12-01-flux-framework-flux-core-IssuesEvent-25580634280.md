---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2022-12-01
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4791
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/4791' target='_blank'>flux-framework/flux-core#4791</a>.

<p>resource module cannot handle drained ranks that are no longer valid</p><small>Problem: on tioga, the Flux config must have recently shrunk as there were drained nodes listed in the `resource.eventlog` whose ranks were >= the instance size.  Instead of ignoring these ranks, flux simply refused to start with an unhelpful invalid argument error:...</small><a href='https://github.com/flux-framework/flux-core/issues/4791' target='_blank'>View Comment</a>