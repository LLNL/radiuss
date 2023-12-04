---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4656391?"
user: wdconinc
date: 2023-12-03
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/41404
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/wdconinc' target='_blank'>wdconinc</a> commented on issue <a href='https://github.com/spack/spack/pull/41404' target='_blank'>spack/spack#41404</a>.

<small>It is a bit problematic to do these 'partial' backports. Say I want to cherry-pick version upgrades in the root package on develop against the v0.21.1 release (I am assuming that's a fairly common workflow), that will now fail because of cherry-pick conflicts. I think the backports should attempt not to break this workflow, and we should aim to backport an entire commit into develop. That's however also problematic in this case since the PR that was merged into develop mixes this security patch with version upgrades. It would have been better to keep the security patch and the version upgrades separate. So, no concrete suggestions from my side but I just wanted to point out the problems I see with this approach in case others have ideas about how to avoid them....</small>

<a href='https://github.com/spack/spack/pull/41404' target='_blank'>View Comment</a>