---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/512185?"
user: BarrySmith
date: 2022-10-31
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/764
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/BarrySmith' target='_blank'>BarrySmith</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/764' target='_blank'>hypre-space/hypre#764</a>.

<small>Note that this kind of memory leak, which happens because we do not call the hypre_finalize(), should be fixed, but it is not a big deal. The problematic memory leaks occur because we are not properly freeing some resources along the way in the computations, so we start wasting more and more memory that is no longer accessible, and eventually, the process runs out of memory.  Are there any of those sorts of memory leaks that we can fix in PETSc? ...</small>

<a href='https://github.com/hypre-space/hypre/issues/764' target='_blank'>View Comment</a>