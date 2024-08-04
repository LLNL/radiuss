---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-08-04
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6179
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6179' target='_blank'>flux-framework/flux-core#6179</a>.

<small>Somehow the job would need to get out of the `hk->allocations` list without going through `allocation_remove()` (which logs that message).  I don't see a way for that to happen, other than if the scheduler were reloaded and the job was partially released or another less likely error, but then we would see another log message...</small>

<a href='https://github.com/flux-framework/flux-core/issues/6179' target='_blank'>View Comment</a>