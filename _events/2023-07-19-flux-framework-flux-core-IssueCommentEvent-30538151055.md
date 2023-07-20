---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2023-07-19
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5345
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5345' target='_blank'>flux-framework/flux-core#5345</a>.

<small>As discussed with @jameshcorbett offline, currently an outstanding `epilog-start` event just prevents the `free` request from being issued to the scheduler. If there is no pending `free` request, i.e. the `free` event does not need to be emitted for the job to proceed to inactive, then an `epilog-start` event has no effect and the `clean` event is emitted....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5345' target='_blank'>View Comment</a>