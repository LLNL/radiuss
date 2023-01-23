---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/95727890?"
user: atallah727
date: 2023-01-23
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3415
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/atallah727' target='_blank'>atallah727</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3415' target='_blank'>mfem/mfem#3415</a>.

<small>Hello @miaodi, you can still do a L2 space for the entire mesh and concurrently create an attribute that checks whether an interior edge fractured or not in the face integrator assembly. If the attribute indicates that the edge fractured, you would activate the cohesive zone model integrals, otherwise you would enforce the standard jump and average terms similar to any DG algorithm....</small>

<a href='https://github.com/mfem/mfem/issues/3415' target='_blank'>View Comment</a>