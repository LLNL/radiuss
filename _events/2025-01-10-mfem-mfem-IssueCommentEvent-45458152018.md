---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2025-01-10
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4545
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>mfem/mfem#4545</a>.

<small>Maybe the fundamental problem here is that you have a system of two equations, which you put into a block and solve them like one, i.e., the solver uses a single norm, which is like ||j|| + ||phi||, which does not make much sense as you are mixing apples with oranges here 🍏 🟠 . It should be more like ||j|| + ||kappa grad phi||, which it actually almost is, because the residuum is measured, so it is more complicated than this, but to give you an idea. It can happen it is insensitive to one of the equations, so you get maybe perfect solution in phi, but poor in j. You are not the only one facing this and there is pull request #4483 for generalization of the norm used by solvers. With that you could decide that the solution is converged only when _both_ quantities are converged....</small>

<a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>View Comment</a>