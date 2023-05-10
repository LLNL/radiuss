---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-05-09
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3611
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3611' target='_blank'>mfem/mfem#3611</a>.

<small>In some further investigations, I have uncovered an issue with `GetVectorValue` when called on face neighbor elements for P2. The basic issue appears to be that `face_nbr_el_to_face` and `face_nbr_el_ori` needs to be populated in `ParMesh`. The calls in sequence trigger:...</small>

<a href='https://github.com/mfem/mfem/pull/3611' target='_blank'>View Comment</a>