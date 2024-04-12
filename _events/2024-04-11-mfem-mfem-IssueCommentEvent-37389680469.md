---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2024-04-11
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4128
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4128' target='_blank'>mfem/mfem#4128</a>.

<small>I think it means that when `Mesh::FinalizeTopology` eventually gets called from `ParMesh::Load`, you will get a call to `Mesh::GenerateBoundaryElements` which is what I thought was what we wanted to avoid....</small>

<a href='https://github.com/mfem/mfem/pull/4128' target='_blank'>View Comment</a>