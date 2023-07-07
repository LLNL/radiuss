---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-07-06
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3766
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3766' target='_blank'>mfem/mfem#3766</a>.

<small>I believe the trickiest part about constructing such a mesh, will be reverse engineering the root mesh structure. I believe it's a fairly low level assumption of the NCMesh structure, that the root mesh (initial elements) form a conformal mesh. In principle it can be done though, I believe by recursively coarsening any nc faces found and counting the number of times any given element needs to be refined to reach the initial state. This bares a lot of similarity to loading an NCMesh from file, it's quite plausible we could reuse that functionality for the construction of the relevant NCMesh member variable. At least for topologically simple boundary meshes....</small>

<a href='https://github.com/mfem/mfem/pull/3766' target='_blank'>View Comment</a>