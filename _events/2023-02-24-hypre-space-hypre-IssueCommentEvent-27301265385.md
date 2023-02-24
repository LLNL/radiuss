---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5429263?"
user: liruipeng
date: 2023-02-24
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/843
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/liruipeng' target='_blank'>liruipeng</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/843' target='_blank'>hypre-space/hypre#843</a>.

<small>Since you are using unified memory, do you modify the vector from the host? Otherwise, I don't see a reason to synchronize unless you have other CUDA kernels in different CUDA streams touching the same vector again. What you may try first is to `--enable-debug` which adds sync. steam at all kernel's completion and see if the error goes away. Hope this can help....</small>

<a href='https://github.com/hypre-space/hypre/issues/843' target='_blank'>View Comment</a>