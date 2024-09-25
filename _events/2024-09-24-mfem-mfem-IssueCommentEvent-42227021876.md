---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10469466?"
user: cjvogl
date: 2024-09-24
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4513
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/cjvogl' target='_blank'>cjvogl</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4513' target='_blank'>mfem/mfem#4513</a>.

<small>> @cjvogl , that makes sense, but where would you put it? It is just an interface, so `FluxFunction::ComputeAvgFlux()` has just `MFEM_ABORT()`. The only implementations are in `AdvectionFlux` and `BurgersFlux`, which are both scalar by construction 🤔 ....</small>

<a href='https://github.com/mfem/mfem/pull/4513' target='_blank'>View Comment</a>