---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/8642948?"
user: bensworth
date: 2022-12-16
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/764
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/bensworth' target='_blank'>bensworth</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/764' target='_blank'>hypre-space/hypre#764</a>.

<small>Great! I will write up a simple example today where two-level AIR is (theoretically) exact in one iteration and should be a good unit test. One other comment : we don't have a block version of AIR in hypre (only in PyAMG), so the work around for DG advective problems is to scale by the (element) block diagonal inverse (this makes the matrix amenable to a scalar as opposed to block reduction method). This is also in hypre, and the MFEM wrapper here: https://github.com/mfem/mfem/blob/master/linalg/hypre.cpp#L2762. It would be nice to have access to this function for DG advective discretizations....</small>

<a href='https://github.com/hypre-space/hypre/issues/764' target='_blank'>View Comment</a>