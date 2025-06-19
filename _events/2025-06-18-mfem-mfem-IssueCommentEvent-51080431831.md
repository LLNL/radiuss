---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/27717785?"
user: justinlaughlin
date: 2025-06-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4326
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/justinlaughlin' target='_blank'>justinlaughlin</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4326' target='_blank'>mfem/mfem#4326</a>.

<small>So this PR adds a lot of the framework (e.g. `fe_nurbs.cpp`) for implementing local NURBS interpolation. What is currently used is (if I'm not mistaken) simply function evaluation at Botella points. Eventually we may decide to update the local interpolation computations to be something more sophisticated (e.g. [Bezier projection](https://www.sciencedirect.com/science/article/pii/S0045782514002448)); but because there is no kronecker delta property for NURBS spaces every local interpolation is ultimately still just an approximation. It could be argued that the L2 projection is the most correct and should remain the default (the counter-argument is that it may be impractical for reasonably sized problems.... I'm okay either way), but I think there are enough useful things we'd like to build off of from this PR to justify merging it without necessarily changing the local interpolation routine....</small>

<a href='https://github.com/mfem/mfem/pull/4326' target='_blank'>View Comment</a>