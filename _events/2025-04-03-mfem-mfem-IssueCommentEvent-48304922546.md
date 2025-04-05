---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10469466?"
user: cjvogl
date: 2025-04-03
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4736
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/cjvogl' target='_blank'>cjvogl</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4736' target='_blank'>mfem/mfem#4736</a>.

<small>I should note using the `NewtonSolver` class with a general preconditioner (e.g., `BlockDiagonalPreconditioner`) and general linear solver (e.g., `GMRES`) doesn't leverage any structure of the coupled problem and will very likely result in the same slow linear solve you experienced in the simple problem... but now at every Newton iteration. If that does happen, you can consider leveraging the structure through either a custom preconditioner or a custom solver. To motivate how this might go, I'll return to your simplified linear problem...</small>

<a href='https://github.com/mfem/mfem/issues/4736' target='_blank'>View Comment</a>