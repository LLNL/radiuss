---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2025-04-26
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4829
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4829' target='_blank'>mfem/mfem#4829</a>.

<small>Sry, I had the timeline wrong, `VectorCoefficient::Project()` was introduced together its specialization for `VectorGridFunctionCoefficient` in #3066 . The thing is there is no easy way for users to project a vector grid function onto a quadrature function as the specialization `VectorGridFunctionCoefficient::Project()` calls `QuadratureFunction::ProjectGridFunction()`, which has limited applicability (as happened here). While the default implementation of  `VectorCoefficient::Project()` would work perfectly fine in those cases (for performance non-critical applications), but the user is left with an error in a better case or silent failure in the worst. @pazner wanted to look at that some time ago, is it still the case? 😉 ...</small>

<a href='https://github.com/mfem/mfem/issues/4829' target='_blank'>View Comment</a>