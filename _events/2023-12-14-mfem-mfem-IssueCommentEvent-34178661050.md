---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11507994?"
user: rw-anderson
date: 2023-12-14
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4014
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/rw-anderson' target='_blank'>rw-anderson</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4014' target='_blank'>mfem/mfem#4014</a>.

<small>> I think a more general fix will be to fix `Mesh::Swap` (used in `ParMesh::RebalanceImpl`) which should handle all lazy-constructed data. In addition to `nbInteriorFaces` and `nbBoundaryFaces`, it looks like `Mesh::Swap` does not handle `face_geom_factors` either, so we should fix that too....</small>

<a href='https://github.com/mfem/mfem/pull/4014' target='_blank'>View Comment</a>