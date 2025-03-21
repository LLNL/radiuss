---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2025-03-19
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4545
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>mfem/mfem#4545</a>.

<small>Looking forward to it. Regarding `IterativeSolverController`, it is very easy. The solver calls `MonitorSolution()`, which gets the intermediate solution and the only thing to implement is evaluation of the norm. If it is lower than your desired threshold, just indicate convergence by setting `converged = true`. The solver checks that and ends the calculation. That is it 😉 ....</small>

<a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>View Comment</a>