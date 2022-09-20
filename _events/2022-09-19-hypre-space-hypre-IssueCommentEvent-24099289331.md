---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2022-09-19
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/735
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/735' target='_blank'>hypre-space/hypre#735</a>.

<small>Hi @ShatrovOA .  What is your stopping tolerance?  If your relative residual is really 1.0e-314, then you have converged.  Since this is a Neumann problem, there are infinitely many solutions.  Most often, people will post process the returned solution by projecting out the null space of the matrix (this is usually the constant vector).  Hope this helps!...</small>

<a href='https://github.com/hypre-space/hypre/issues/735' target='_blank'>View Comment</a>