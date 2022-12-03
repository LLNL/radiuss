---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2022-12-02
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/4776
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/4776' target='_blank'>flux-framework/flux-core#4776</a>.

<small>re-pushed, with lots of fixes given above comments / discussion.  Besides the code cleanup, the big change is how to solve the `flux queue stop` during shutdown problem.  Added a `nocheckpoint` flag to the `queue-start` RPC and a `--nocheckpoint` option to `flux queue stop`.  Implemented a "shadow value" to store the checkpointing value per discussion above.   It ended up being way simpler than I thought it would be....</small>

<a href='https://github.com/flux-framework/flux-core/pull/4776' target='_blank'>View Comment</a>