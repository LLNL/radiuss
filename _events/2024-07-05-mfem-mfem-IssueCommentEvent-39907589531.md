---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2024-07-05
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4382
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4382' target='_blank'>mfem/mfem#4382</a>.

<small>Yes, this coefficient should be exact (at a given point, it should evaluate exactly the term $q \nabla T$). In order to compute the integrals in the linear form exactly, you will need to make sure that the quadrature rule used in the integrator is sufficiently accurate to integrate terms of the form $(q \nabla T) v$ (potentially with the additional contribution of the mesh Jacobians)....</small>

<a href='https://github.com/mfem/mfem/issues/4382' target='_blank'>View Comment</a>