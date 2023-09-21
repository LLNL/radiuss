---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2023-09-20
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5460
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5460' target='_blank'>flux-framework/flux-core#5460</a>.

<small>Looking at the ompi source  referenced above it seems that `opal_common_ucx_del_procs()` first calls `opal_common_ucx_del_procs_nofence()`, then calls the `opal_common_ucx_mca_pmix_fence()` (which executes the pmi barrier).  Traces show one rank that made it all the way to the PMI barrier, and the other ranks stuck in `opal_common_ucx_del_procs_nofence()` -> `opal_common_ucx_wait_all_requests()`....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5460' target='_blank'>View Comment</a>