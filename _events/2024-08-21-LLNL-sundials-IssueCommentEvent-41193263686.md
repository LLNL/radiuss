---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11356722?"
user: Steven-Roberts
date: 2024-08-21
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/pull/463
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/Steven-Roberts' target='_blank'>Steven-Roberts</a> commented on issue <a href='https://github.com/LLNL/sundials/pull/463' target='_blank'>LLNL/sundials#463</a>.

<small>After some more thought and discussion with David on IDA and passing around `yp`, the primary issue I see is keeping it consistent with `y`. With operator splitting, for example, `y` jumps around between calls to evolve, and I don't see how to keep `yp` consistent. With MRI, the change in the forcing between stages can cause a similar issue. This is not something the outer methods can do and needs to be done in the inner SunStepper integrator....</small>

<a href='https://github.com/LLNL/sundials/pull/463' target='_blank'>View Comment</a>