---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2022-12-12
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/779
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/779' target='_blank'>hypre-space/hypre#779</a>.

<small>> @rfalgout The crash with OpenMP was due to a bug on `hypre_IJMatrixAddToValuesOMPParCSR`: the pointer `my_offproc_cnt` was being realloced, but its new address was not being saved at `offproc_cnt[my_thread_num]`....</small>

<a href='https://github.com/hypre-space/hypre/pull/779' target='_blank'>View Comment</a>