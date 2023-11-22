---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/22107593?"
user: thartland
date: 2023-11-21
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1014
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/thartland' target='_blank'>thartland</a> open issue <a href='https://github.com/hypre-space/hypre/issues/1014' target='_blank'>hypre-space/hypre#1014</a>.

<p>Question on how to setup a HYPRE_IJMatrix with one row</p><small>I want to setup a $1 \times n$ `HYPRE_IJMatrix`. My main concern is how to determine `rowOffsets`, if I choose (as in the code below) `rowOffsets[0] = rowOffsets[1] = 0`, then each MPI process will own the `0`th row. I would prefer that only the root MPI process owns the `0`th row but am not sure how to do that. I haven't run into any bugs yet but I keep thinking that there must be a better way to do things and would like to avoid future issues. I have attached a simple example code to illustrate what I have in context of what I would like to do....</small><a href='https://github.com/hypre-space/hypre/issues/1014' target='_blank'>View Comment</a>