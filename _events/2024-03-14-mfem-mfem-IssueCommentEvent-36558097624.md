---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2024-03-14
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4186
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4186' target='_blank'>mfem/mfem#4186</a>.

<small>I don't think it makes sense for `QuadratureSpace` to have a `vdim`. It's common to need many different `vdim` quantities at the same quadrature points. For example, you might have matrices, vectors, and scalars all living at the same quadrature points — it's convenient for all of these to share the same `QuadratureSpace`. The main purpose for `QuadratureSpace` is to associate to every element in the mesh a quadrature rule. The `vdim` of the fields is orthogonal to this concept....</small>

<a href='https://github.com/mfem/mfem/issues/4186' target='_blank'>View Comment</a>