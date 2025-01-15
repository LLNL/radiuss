---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2025-01-14
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4662
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4662' target='_blank'>mfem/mfem#4662</a>.

<small>Yes, the CG solver uses its second argument as an initial guess (when iterative mode is true). In your case, the vector probably has some uninitialized memory that sometimes gives NaNs, causing the error. I would just set the vector to zero immediately before calling the solver....</small>

<a href='https://github.com/mfem/mfem/issues/4662' target='_blank'>View Comment</a>