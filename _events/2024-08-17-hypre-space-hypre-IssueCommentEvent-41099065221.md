---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2024-08-17
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/1112
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/1112' target='_blank'>hypre-space/hypre#1112</a>.

<small>Okay, now I see where this happens.  We've never used environment variables to control the way hypre behaves.  I'm not sure it's a path we should go down.  Why not define a hypre handle routine to set this (e.g., like HYPRE_SetUseGpuRand)?  The user's driver code could then control things via an environment variable (if preferred) that they 'getenv' and pass to hypre through this function.  Once the code is written the first time, no user code changes are required, right?  In addition, users could choose to control this functionality in other ways such as on the command line or through an input file, etc....</small>

<a href='https://github.com/hypre-space/hypre/pull/1112' target='_blank'>View Comment</a>