---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5429263?"
user: liruipeng
date: 2025-04-10
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1265
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/liruipeng' target='_blank'>liruipeng</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1265' target='_blank'>hypre-space/hypre#1265</a>.

<small>> [@ictmay](https://github.com/ictmay) The `SetRAP2` call defaults to zero internally. It doesn't seem to be necessary for GPUs anymore, i.e., either 0 or 1 work fine (we will need to update the documentation). However, it's important to have `hypre_BoomerAMGSetModuleRAP2` set to 1, which is also the default internally (hypre) for GPUs in case you don't call it already in your code. cc [@liruipeng](https://github.com/liruipeng)...</small>

<a href='https://github.com/hypre-space/hypre/issues/1265' target='_blank'>View Comment</a>