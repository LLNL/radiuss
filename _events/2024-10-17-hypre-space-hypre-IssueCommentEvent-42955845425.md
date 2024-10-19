---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20098718?"
user: waynemitchell
date: 2024-10-17
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/1141
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/waynemitchell' target='_blank'>waynemitchell</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/1141' target='_blank'>hypre-space/hypre#1141</a>.

<small>Looks like the issue wasn't actually sycl-related. I think there was just one call to hypre_SyncComputeStream() that didn't get updated and still had the handle arg. So the compile failed. I went ahead and merged the most recent master and fixed that one function call. Running the sycl regressions now....</small>

<a href='https://github.com/hypre-space/hypre/pull/1141' target='_blank'>View Comment</a>