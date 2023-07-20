---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2023-07-19
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5345
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5345' target='_blank'>flux-framework/flux-core#5345</a>.

<small>I did notice that the dws plugin is calling `flux_jobtap_prolog_start()` from the `job.state.cleanup` callback, while `perilog` calls it from  `job.event.finish`.   It does seem like either ought to work but perhaps changing it would be a quick fix, since perilog is pretty well tested (in fact I just tested that case on my test cluster)....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5345' target='_blank'>View Comment</a>