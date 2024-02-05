---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/9196588?"
user: termi-official
date: 2024-02-04
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4072
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/termi-official' target='_blank'>termi-official</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4072' target='_blank'>mfem/mfem#4072</a>.

<small>1D-3D coupling is indeed a bit tricky (in every framework). I think easiest way would be to have a 3D mesh with fine elements near the 1D source and give the 1D source a finite thickness. This way you can take all quadrature points in the 3D mesh and search for the nearest 1D element. If the 1D element is smaller than the thickness of the element, then you can compute the source contribution coming from this 1D element. This way you will obtain a sound coupling, but it is a bit costly. Maybe it also needs to be paired with AMR if you need higher precision....</small>

<a href='https://github.com/mfem/mfem/issues/4072' target='_blank'>View Comment</a>