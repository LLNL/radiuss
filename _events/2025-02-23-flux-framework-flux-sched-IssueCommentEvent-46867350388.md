---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-02-23
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1344
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1344' target='_blank'>flux-framework/flux-sched#1344</a>.

<small>Just starting to look at this and it appears `remove()` requires a jobid, which doesn't make sense  when shrinking the available resources (there could in practice be multiple jobs with active allocations on the shink targets). It doesn't look like `partial_cancel` actually uses the jobid, but `remove()` does....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1344' target='_blank'>View Comment</a>