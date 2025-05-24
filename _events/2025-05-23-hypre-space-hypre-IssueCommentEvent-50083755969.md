---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20098718?"
user: waynemitchell
date: 2025-05-23
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/1287
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/waynemitchell' target='_blank'>waynemitchell</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/1287' target='_blank'>hypre-space/hypre#1287</a>.

<small>@rfalgout, OK, I'm mostly documenting this for my own understanding (I think you know all this already). I did some testing to verify this. The fix here in coarsen.c affects the correctness of the specialized matmult routine AND has an impact on the ssamg hierarchy. That is why even if you are using the general/slower matmult code path (which always yields correct matmults), the fix can still yield a difference in convergence. Out of curiosity, do you know exactly how the incorrect pbnd boxes were affecting the ssamg hierarcy? I guess that they will affect how the interpolation operator is setup, since you do some adjustment of weights at the part boundaries defined by these boxes. Anything else?...</small>

<a href='https://github.com/hypre-space/hypre/pull/1287' target='_blank'>View Comment</a>