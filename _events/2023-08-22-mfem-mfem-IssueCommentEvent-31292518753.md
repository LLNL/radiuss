---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2023-08-22
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3838
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3838' target='_blank'>mfem/mfem#3838</a>.

<small>Hi Joe, this issue actually does not arise due to the ordering of nodes in the mesh but rather due to ordering of degrees of freedom on each element. Non-hexahedron elements don't have support for `mfem::ElementDofOrdering::LEXICOGRAPHIC` (they only support `mfem::ElementDofOrdering::NATIVE`). ...</small>

<a href='https://github.com/mfem/mfem/issues/3838' target='_blank'>View Comment</a>