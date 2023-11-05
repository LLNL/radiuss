---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-11-05
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3963
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3963' target='_blank'>mfem/mfem#3963</a>.

<small>@rw-anderson, this same issue came up in some debugging we did with @artv3. What you propose seems a good solution -- I think it may be better to add `ResetLazyData()` call to `ParMesh::NonconformingRefinement()` instead of moving the call up to `Mesh::GeneralRefinement()` since this way the protected refinement methods will be correct on their own....</small>

<a href='https://github.com/mfem/mfem/issues/3963' target='_blank'>View Comment</a>