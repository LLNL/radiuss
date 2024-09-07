---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-09-06
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4479
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4479' target='_blank'>mfem/mfem#4479</a>.

<small>This requires some form of re-partitioning for the ParMesh which is currently possible only if you convert the serial mesh to nonconforming mesh, e.g. using `EnsureNCMesh()`. You can then use a custom partitioning array to distribute the serial mesh to 4 processors assigning 0 elements to the remaining 16-4=12 ranks. After parallel refinement, you can re-partition the mesh to 16 ranks using `Rebalance(const Array<int> &partition)`....</small>

<a href='https://github.com/mfem/mfem/issues/4479' target='_blank'>View Comment</a>