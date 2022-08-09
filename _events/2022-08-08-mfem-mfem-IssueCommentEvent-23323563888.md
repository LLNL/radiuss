---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5412886?"
user: jandrej
date: 2022-08-08
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3130
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/jandrej' target='_blank'>jandrej</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3130' target='_blank'>mfem/mfem#3130</a>.

<small>#2613 aren't reviewed changes. There was no thorough process to check if those changes actually work like intended. The approach that you took seems reasonable. The "discontinuous look" in your velocity indicates an error in the integrator though. It seems like the interior and exterior face terms are not properly contributing to the residual. I know this isn't much input, but we probably need a while to take a deeper look at the problem....</small>

<a href='https://github.com/mfem/mfem/issues/3130' target='_blank'>View Comment</a>