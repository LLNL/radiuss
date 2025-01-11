---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/194184317?"
user: Fei-GEO
date: 2025-01-10
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4658
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/Fei-GEO' target='_blank'>Fei-GEO</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4658' target='_blank'>mfem/mfem#4658</a>.

<small>> Hi, I just fixed the latex, I hope it is correct. Can you tell us more about your discretization? Do you construct a block operator/matrix? What integrators do you use? However, I would say it is not a good idea to separate the equations. It is a tightly coupled system of electric diffusion, so parabolic PDE. Poor performance with Hdiv is understandable, because you cannot precisely construct electric current (from electric field) even with scalar conductivity as there is a (re)interpolation error....</small>

<a href='https://github.com/mfem/mfem/issues/4658' target='_blank'>View Comment</a>