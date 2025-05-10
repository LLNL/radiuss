---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/34784921?"
user: rchen20
date: 2025-05-08
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1830
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rchen20' target='_blank'>rchen20</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1830' target='_blank'>LLNL/RAJA#1830</a>.

<small>I've tried @v-dobrev's suggestions in RAJA, and have still come to the same conclusion that we are better off keeping our pragmas the same as before. There are 2 problems when using the GCC unroll in the 1-a and 2-a cases. First, while g++ compilation is happy, the pragma is still propagated to our device code, so pure device code obtains the GCC unrolling pragma and is not unrolled:...</small>

<a href='https://github.com/LLNL/RAJA/issues/1830' target='_blank'>View Comment</a>