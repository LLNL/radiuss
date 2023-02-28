---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6109571?"
user: mlstowell
date: 2023-02-27
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3450
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/mlstowell' target='_blank'>mlstowell</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3450' target='_blank'>mfem/mfem#3450</a>.

<small>@YohannDudouit, you make many good points but the solution proposed in this PR will break other user's code. Consider someone whose code uses `Mesh::GetVertex` to access the coordinates of the first order nodes directly. After calling, perhaps indirectly, your proposed `const` method `Mesh::GetNodalFESpace()` their vertices are suddenly and inexplicably abandoned. The vertex coordinate arrays still contain data but that data will no longer be updated if the mesh geometry changes. That is going to be a much harder bug to track down than unexpectedly accessing a NULL pointer....</small>

<a href='https://github.com/mfem/mfem/pull/3450' target='_blank'>View Comment</a>