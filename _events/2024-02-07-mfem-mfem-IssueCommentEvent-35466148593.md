---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6109571?"
user: mlstowell
date: 2024-02-07
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4113
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/mlstowell' target='_blank'>mlstowell</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4113' target='_blank'>mfem/mfem#4113</a>.

<small>The reason this came up in the `ParSubMesh` context is that when an interior boundary is also a boundary of a `ParSubMesh` the boundary elements along processor boundaries will sometimes not appear in the `ParSubMesh` with the same boundary attribute that they had in the parent mesh. Any interior boundary elements that get dropped will appear in the `ParSubMesh` as newly identified boundary elements with no association to the original interior boundary and therefore they are given a new attribute number....</small>

<a href='https://github.com/mfem/mfem/pull/4113' target='_blank'>View Comment</a>