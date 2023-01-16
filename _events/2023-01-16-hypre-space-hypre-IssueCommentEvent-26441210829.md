---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/59861949?"
user: zongy17
date: 2023-01-16
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/822
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/zongy17' target='_blank'>zongy17</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/822' target='_blank'>hypre-space/hypre#822</a>.

<small>Finally I fixed it. It was a bug in my code to define stencil offsets. There were 27 group of offsets in total, each consists of 3 int. I provided two same offsets within 27 as a mistake, and thus neglected another one in 27. HYPRE treated it as 3d27 pattern, and accessed its pointers through funtion hypre_StructMatrixExtractPointerByIndex. The function call corresponding to the neglected one would return a NULL pointer, and cause following segfault when HYPRE tried accessing values inside this pointer....</small>

<a href='https://github.com/hypre-space/hypre/issues/822' target='_blank'>View Comment</a>