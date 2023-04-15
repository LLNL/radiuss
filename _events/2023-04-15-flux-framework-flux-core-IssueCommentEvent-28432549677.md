---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2023-04-15
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5081
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5081' target='_blank'>flux-framework/flux-core#5081</a>.

<small>seems reasonable to me, all that would have to be adjusted is `wallclock_get_zulu()`'s use of `gmtime` and use `localtime` instead (and we should probably rename the function too, since "zulu time" wouldn't make any sense anymore)....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5081' target='_blank'>View Comment</a>