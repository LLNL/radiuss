---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-01-30
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5201
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5201' target='_blank'>flux-framework/flux-core#5201</a>.

<small>Idea: add a new job state RESERVED between SCHED and RUN such that a  job request with a special attribute could get its alloc response _R_ from the scheduler early, in advance of the the `starttime` field in _R_,.  The job manager and the rest of flux could just treat that like any other allocation, except the job would remain in RESERVED state until `starttime` arrives.  With _R_ stored in the KVS, the `sched.hello` protocol could throw it back to the scheduler on a restart....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5201' target='_blank'>View Comment</a>