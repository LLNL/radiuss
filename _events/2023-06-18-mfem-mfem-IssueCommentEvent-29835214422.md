---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-06-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3083
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3083' target='_blank'>mfem/mfem#3083</a>.

<small>> I would think the simplest approach you suggest is to just copy the Hypre allocated data into new arrays which are SuperLU_DIST allocated at the expense of an extra copy, as in the first `SuperLURowLocMatrix` constructor. This is what, for example, the STRUMPACK and MUMPS solvers do rather than taking ownership of the input pointers. This way we can always guarantee that the malloc/free done are done in a compatible way by SuperLU_DIST....</small>

<a href='https://github.com/mfem/mfem/pull/3083' target='_blank'>View Comment</a>