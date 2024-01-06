---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-01-06
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5658
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5658' target='_blank'>flux-framework/flux-core#5658</a>.

<small>Ah, this is probably because the message raising the exception comes from the job-exec module, which doesn't go through the local connector, so the message credential is uninitialized. Maybe we should use the result of `getuid()` when `cred.userid` is `FLUX_USERID_UNKNOWN`...</small>

<a href='https://github.com/flux-framework/flux-core/issues/5658' target='_blank'>View Comment</a>