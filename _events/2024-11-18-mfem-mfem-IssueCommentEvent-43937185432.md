---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-11-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4545
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>mfem/mfem#4545</a>.

<small>Hmm, you are right, something is causing MINRES to diverge/crash. I would need to investigate. It might be zero diagonal elements of the matrix corresponding to boundary DOFs. Some solvers are ok with that, but some do division by the diagonal leading to NaNs. However, you may use MINRES with reduction 😉 ....</small>

<a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>View Comment</a>