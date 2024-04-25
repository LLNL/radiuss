---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5412886?"
user: jandrej
date: 2024-04-25
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4258
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/jandrej' target='_blank'>jandrej</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4258' target='_blank'>mfem/mfem#4258</a>.

<small>If the mesh is actually distributed, the element numbers don't match on each MPI rank. That part of the algorithm is basically missing. gslib knows which element it found on what MPI rank but the gather/scatter requires a custom data package to be communicated. We're currently trying to get gslib to accommodate that....</small>

<a href='https://github.com/mfem/mfem/issues/4258' target='_blank'>View Comment</a>