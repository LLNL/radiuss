---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-07-11
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4396
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4396' target='_blank'>mfem/mfem#4396</a>.

<small>I agree, in the iterative solvers, it will be better to not use `MFEM_ASSERT`/`MFEM_VERIFY` but to stop the iteration, record an error condition, print a warning/error message (if the solver is configured to do that), and return from the `Mult` method....</small>

<a href='https://github.com/mfem/mfem/issues/4396' target='_blank'>View Comment</a>