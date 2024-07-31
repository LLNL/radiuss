---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11356722?"
user: Steven-Roberts
date: 2024-07-30
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/pull/548
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/Steven-Roberts' target='_blank'>Steven-Roberts</a> commented on issue <a href='https://github.com/LLNL/sundials/pull/548' target='_blank'>LLNL/sundials#548</a>.

<small>The behavior of pow, abs, min, max, and other functions for inf/nan is specified by the C standard, so I'm not too worried about that. I think a unit test where the error is 0 is warranted to double check. The standard only specifies that `pow(0, 0)` may cause a domain error (and doesn't even specify what the value could be), and `pow(0, y)` can cause floating point exceptions for certain `y`. I think I'll need to handle that more carefully in the controller....</small>

<a href='https://github.com/LLNL/sundials/pull/548' target='_blank'>View Comment</a>