---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2025-01-29
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3525
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3525' target='_blank'>mfem/mfem#3525</a>.

<small>One additional difficulty of going to `SubMesh` entirely for this, is it would require submesh for internal nonconforming boundaries, which is not currently supported. In palace we also moved away from the scale modification approach in favour of pre and post mutating the mesh, as it worked cleaner with saving and repartitioning meshes, at the cost of a relatively small amount of extra (embarassingly parallel) computation....</small>

<a href='https://github.com/mfem/mfem/pull/3525' target='_blank'>View Comment</a>