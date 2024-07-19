---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-07-18
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6119
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6119' target='_blank'>flux-framework/flux-core#6119</a>.

<p>`flux resource list -i INCLUDE` shows draining resources in down & allocated instead of draining</p><small>`flux resource list -i` shows targets that are drained and allocated (i.e. draining) as both drained and allocated, instead of using a `draining` virtual state. I think in normal usage `flux resource list` shows those resources on the appropriate `draining` line, but something must be missing with the `--include` logic....</small><a href='https://github.com/flux-framework/flux-core/issues/6119' target='_blank'>View Comment</a>