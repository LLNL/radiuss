---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-05-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4271
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4271' target='_blank'>mfem/mfem#4271</a>.

<small>I noticed a potential issue when `SymmetricMatrixCoefficient::ProjectSymmetric` is called with `QuadratureFunction &qf` that is valid on device. Since we are accessing its entries using aliases, and all of that is done on host, it is best to call...</small>

<a href='https://github.com/mfem/mfem/pull/4271' target='_blank'>View Comment</a>