---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2023-02-20
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/839
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/839' target='_blank'>hypre-space/hypre#839</a>.

<small>Hi @johannjc .  The function your fortran code is linking to is actually in `struct_mv/F90_HYPRE_struct_stencil.c` and calls the create function defined in `HYPRE_struct_stencil.c`.  In looking at the above, I think the issue may be that you are defining the `stencil` component of your derived type to be `integer(8)` instead of `integer*8`.  The first is an array of integers, right?  Anyway, that's my best guess.  Hope this helps!...</small>

<a href='https://github.com/hypre-space/hypre/issues/839' target='_blank'>View Comment</a>