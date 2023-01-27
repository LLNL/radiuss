---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/95727890?"
user: atallah727
date: 2023-01-27
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3415
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/atallah727' target='_blank'>atallah727</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3415' target='_blank'>mfem/mfem#3415</a>.

<small>I don't think there examples on that, but you can check the Get/SetBdrAttribute in the mesh.hpp file and do something similar for the interior faces. Be careful to call pmesh->ExchangeFaceNbrNodes()to make the marking is communicated to the processors that share edges. In regards to you second question, this is something we are considering, but so far there are no initiatives in that direction. ...</small>

<a href='https://github.com/mfem/mfem/issues/3415' target='_blank'>View Comment</a>