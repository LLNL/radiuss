---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2024-10-15
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4371
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4371' target='_blank'>mfem/mfem#4371</a>.

<small>> @hughcars The series of refinements you described is actually not possible, which is a different problem. I modified `ref321` to perform these refinements, and the Y-refinement of the right element does not introduce a new vertex. Instead, it identifies the vertices for the left and right refinements, putting them at the same location. I will have to think about how to handle this case....</small>

<a href='https://github.com/mfem/mfem/pull/4371' target='_blank'>View Comment</a>