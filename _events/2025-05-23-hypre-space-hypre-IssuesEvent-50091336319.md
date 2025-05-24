---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2025-05-23
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1288
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> open issue <a href='https://github.com/hypre-space/hypre/issues/1288' target='_blank'>hypre-space/hypre#1288</a>.

<p>hypre_BoomerAMGSetupStats can be very slow on device</p><small>In BoomerAMG setup (`hypre_BoomerAMGSetup`), if print level is 1 or 3, the AMG hierarchy matrix statistics will be printed out with `hypre_BoomerAMGSetupStats`. On device, this will end up copying the AMG object to host to compute the statistics, which in some benchmarking with @liruipeng we saw as taking longer than all the rest of the setup....</small><a href='https://github.com/hypre-space/hypre/issues/1288' target='_blank'>View Comment</a>