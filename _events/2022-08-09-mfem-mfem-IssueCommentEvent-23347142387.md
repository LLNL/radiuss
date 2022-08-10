---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2022-08-09
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3130
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3130' target='_blank'>mfem/mfem#3130</a>.

<small>I will second what @jandrej has said, based on the plot of the velocity, it does look like there is a problem with a face integrator. In particular, I remember that I had some issues with the `DGJumpJumpIntegrator` from @2613 at some point. You could try debugging by comparing with `DGDiffusionIntegrator` with the non-jump-jump terms deleted....</small>

<a href='https://github.com/mfem/mfem/issues/3130' target='_blank'>View Comment</a>