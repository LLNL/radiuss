---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5412886?"
user: jandrej
date: 2024-02-08
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4113
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/jandrej' target='_blank'>jandrej</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4113' target='_blank'>mfem/mfem#4113</a>.

<small>> If I understand correctly, I agree with this proposal. I suggest: 2. That there should be no duplication introduced in the `Mesh::boundary` array so fundamentally no behavior downstream changes. 2. (Related to 1) The list of ghost boundary elements be added to `ParMesh`, not `Mesh`, as they are not needed in the serial case. Then the `ParSubMesh` constructor can pull from those ghost elements as needed....</small>

<a href='https://github.com/mfem/mfem/pull/4113' target='_blank'>View Comment</a>