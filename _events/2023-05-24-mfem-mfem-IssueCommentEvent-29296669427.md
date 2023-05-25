---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2023-05-24
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/2806
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/issues/2806' target='_blank'>mfem/mfem#2806</a>.

<small>I suppose what you need to do is loop over each face of the element, and determine whether the face is in the interior or on the boundary (i.e., does it have one neighboring element or two), and then compute the surface area (by summing the Jacobian determinant weighted by the quadrature weights)....</small>

<a href='https://github.com/mfem/mfem/issues/2806' target='_blank'>View Comment</a>