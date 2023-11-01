---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2023-11-01
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/5522
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/5522' target='_blank'>flux-framework/flux-core#5522</a>.

<small>Based on some offline discussion with @garlick, I've just force-pushed an update that modifies how the job-exec module is notified of job expiration updates. In the previous iteration of this PR, the job-exec module used the `job-info.update-watch` service to watch for R updates. However, this resulted in the module getting an extra RPC response for every job since he job-manager already includes R in the initial `start` request, and the job-info module will always reply at least to the `job-info.update-watch` RPC with the initial version of R....</small>

<a href='https://github.com/flux-framework/flux-core/pull/5522' target='_blank'>View Comment</a>