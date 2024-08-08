---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2024-08-07
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4416
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4416' target='_blank'>mfem/mfem#4416</a>.

<small>Yes, that sounds fine to me. `BuildDofToBdrArrays` would be made private, `BuildDofToArrays` remains public but deprecated, and an additional "internal" `BuildDofToArrays_` would be added (called by `GetElementForDof` and `GetLocalDofForDof`)....</small>

<a href='https://github.com/mfem/mfem/pull/4416' target='_blank'>View Comment</a>