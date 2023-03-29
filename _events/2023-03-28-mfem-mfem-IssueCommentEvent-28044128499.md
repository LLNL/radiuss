---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-03-28
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/2666
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/issues/2666' target='_blank'>mfem/mfem#2666</a>.

<small>Commenting out the assert (I believe this is just to warn that Append would've had to allocate), I believe I have made a little more progress. I believe the real issue is related to the "edge-face" constraint as described [here](https://github.com/mfem/mfem/pull/713#issuecomment-495786362). In particular [this line](https://github.com/mfem/mfem/blob/master/mesh/ncmesh.cpp#L3023) is introducing the possibility of negative indices being stored in slave.index, which when passed to [this line](https://github.com/mfem/mfem/blob/master/mesh/pncmesh.cpp#L1093) blows up. ...</small>

<a href='https://github.com/mfem/mfem/issues/2666' target='_blank'>View Comment</a>