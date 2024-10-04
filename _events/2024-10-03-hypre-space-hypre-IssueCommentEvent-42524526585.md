---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/50467563?"
user: victorapm
date: 2024-10-03
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1129
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/victorapm' target='_blank'>victorapm</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1129' target='_blank'>hypre-space/hypre#1129</a>.

<small>Hi @marcosvanella, that error should go away after you compile hypre with unified memory support. Let me know if you still have problems. Note the GPU usage in the examples is currently not optimal and we plan to add specific GPU examples with best practices in the future. For example, when assembling matrices on device memory, you should call `HYPRE_IJMatrixSetValues` or `HYPRE_IJMatrixAddToValues` with input data corresponding to several rows instead of one  row at a time as currently being done in the examples, which is fine for CPUs though....</small>

<a href='https://github.com/hypre-space/hypre/issues/1129' target='_blank'>View Comment</a>