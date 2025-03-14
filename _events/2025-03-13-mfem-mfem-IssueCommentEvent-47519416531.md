---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20151415?"
user: emorell96
date: 2025-03-13
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4736
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/emorell96' target='_blank'>emorell96</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4736' target='_blank'>mfem/mfem#4736</a>.

<small>I think I have kind of solved the problem. But the solver is very slow. I'd like ideally to use a NewtonSolver but with the BlockOperator the Gradient operator is not overridden. How can I use the NewtonSolver with this? Can I create a class that inherits BlockOperator and overrides GetGradient? How would you even define that Gradient? Finally I don't see how I can apply the BlockOperator to a non linear equation, since I can't get the sparse matrix from a NonLinearForm to form the block operator. Any help would be appreciated....</small>

<a href='https://github.com/mfem/mfem/issues/4736' target='_blank'>View Comment</a>