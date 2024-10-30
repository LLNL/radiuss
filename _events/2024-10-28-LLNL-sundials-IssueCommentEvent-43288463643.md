---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/33010171?"
user: maggul
date: 2024-10-28
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/pull/541
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/maggul' target='_blank'>maggul</a> commented on issue <a href='https://github.com/LLNL/sundials/pull/541' target='_blank'>LLNL/sundials#541</a>.

<small>I have completed my revision of the PR. @gardner48, thanks for your comments on the RHS evaluations. I’ve found a way to reduce one more line of vectors, which aligns better with our low-storage claim. This new approach involves recomputing `fn` if the step fails, which should be infrequent, thereby reducing the extra line of vectors that would otherwise be needed to store `fn`. Please review the updates and let me know if there’s anything else you need me to address. @drreynolds @balos1 @Steven-Roberts...</small>

<a href='https://github.com/LLNL/sundials/pull/541' target='_blank'>View Comment</a>