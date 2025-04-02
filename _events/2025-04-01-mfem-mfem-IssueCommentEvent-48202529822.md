---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2025-04-01
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4545
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>mfem/mfem#4545</a>.

<small>Hi, the answer is yes and no as usual 🙂 . It does not "drive" the solver as the solver uses its standard integral norm. My thinking was the same and I have tried to redefine the dot product [here in 4483](https://github.com/mfem/mfem/pull/4483#issuecomment-2450834669), but I would not recommend that as the results were poor usually. It is better to keep the solver using the native dot product/norm, but change the norm for the threshold. As we could see, you had very low number of iterations, but the "converged" solution was still poor. The problem is insensitivity of the norm, where the negligible errors in the background have the roughly same weight as the critical errors in the conductor. You can maybe mimic that for a particular case by lower `rtol` (`atol` you have zero, right?), but there is a risk of random accumulation of errors near the machine precision limit. So I would give a try to what was suggested above ☝  It should be straightforward. I might get to it later, but I am at a conference and busy with other things now....</small>

<a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>View Comment</a>