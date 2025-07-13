---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-07-12
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6909
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6909' target='_blank'>flux-framework/flux-core#6909</a>.

<small>To summarize offline debugging, it was discovered via running `rpm --verify` that `/etc/flux/rc1` and `/etc/flux/rc3` had been modified by configuration management and thus the system was running with v0.74.0 with the rc scripts from `v0.71.0`. This caused the `sdmon` modules to not be loaded, so the instance was stuck waiting for `sdmon` to check in....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6909' target='_blank'>View Comment</a>