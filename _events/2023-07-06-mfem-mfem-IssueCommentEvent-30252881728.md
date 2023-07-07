---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6109571?"
user: mlstowell
date: 2023-07-06
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3524
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/mlstowell' target='_blank'>mlstowell</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3524' target='_blank'>mfem/mfem#3524</a>.

<small>Okay, the problem arises because of an incorrect assumption in the `HypreAMS` solver which can be found [here](https://github.com/mfem/mfem/blob/ef6074c42089a7a0eceaa8d12f69ba8462eaa26e/linalg/hypre.cpp#L5451). This line assumes that the number of components in the vector field matches the space dimension....</small>

<a href='https://github.com/mfem/mfem/pull/3524' target='_blank'>View Comment</a>