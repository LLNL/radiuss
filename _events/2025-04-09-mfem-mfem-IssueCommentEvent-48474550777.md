---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/76020022?"
user: adam-sim-dev
date: 2025-04-09
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3568
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/adam-sim-dev' target='_blank'>adam-sim-dev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3568' target='_blank'>mfem/mfem#3568</a>.

<small>> Okay, this makes sense now. One way you could do this with the existing interface is to transform your `shape` matrix. The correct call should be `doftrans->TransformDualRows(shape);`. This replaces the `DenseMatrix shape` with the product `shape * transform`. If you need to recompute `shape` at multiple integration points you would need to call `doftrans->TransformDualRows(shape);` for each `shape` matrix but this should be more efficient than performing a matrix-matrix multiply....</small>

<a href='https://github.com/mfem/mfem/issues/3568' target='_blank'>View Comment</a>