---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/50467563?"
user: victorapm
date: 2022-12-11
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/779
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/victorapm' target='_blank'>victorapm</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/779' target='_blank'>hypre-space/hypre#779</a>.

<small>@rfalgout The crash with OpenMP was due to a bug on `hypre_IJMatrixAddToValuesOMPParCSR`: the pointer `my_offproc_cnt` was being realloced, but its new address was not being saved at `offproc_cnt[my_thread_num]`. I fixed this in the commit [a610454](https://github.com/hypre-space/hypre/pull/779/commits/a610454c89a020c3c9340b9328efd3bcba3f4e0b)....</small>

<a href='https://github.com/hypre-space/hypre/pull/779' target='_blank'>View Comment</a>