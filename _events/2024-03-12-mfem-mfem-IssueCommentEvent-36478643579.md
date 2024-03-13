---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5412886?"
user: jandrej
date: 2024-03-12
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4186
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/jandrej' target='_blank'>jandrej</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4186' target='_blank'>mfem/mfem#4186</a>.

<small>> One option that will be backward compatible is to introduce `VectorQuadratureSpace` -- it will contain a pointer to `QuadratureSpace` and variable `vdim`. Then we can add convenience constructors and other methods in `QuadratureFunction` that take `VectorQuadratureSpace` instead of `QuadratureSpace` and `vdim`. This way `QuadratureSpace` can still be reused for different `vdim` and we have one object that combines `QuadratureSpace` and `vdim`....</small>

<a href='https://github.com/mfem/mfem/issues/4186' target='_blank'>View Comment</a>