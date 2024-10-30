---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2024-10-29
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/1171
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/1171' target='_blank'>hypre-space/hypre#1171</a>.

<small>Another note about printing error messages...  We could modify the routine `HYPRE_PrintErrorMessages()` to be a non-collective routine callable from any rank (to do that, we only need to remove an MPI_Barrier call from the current implementation).  Then the user can decide if they only want to print messages on rank zero.  Messages generated on non-zero ranks (and not also on rank zero) would be missed, of course....</small>

<a href='https://github.com/hypre-space/hypre/pull/1171' target='_blank'>View Comment</a>