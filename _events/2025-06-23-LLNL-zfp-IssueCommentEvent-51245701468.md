---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2025-06-23
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/270
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/270' target='_blank'>LLNL/zfp#270</a>.

<small>Ah, this indeed is necessary as the integral promotion does not extend the right-hand-side operand of `&` with one-bits, as needed to keep all the MSBs in the 64-bit left-hand-side operand.  We have a C++ `zfp::internal::round_up()` utility function for this, and it might make sense to write one for C also so we don't have to play all these casting games....</small>

<a href='https://github.com/LLNL/zfp/issues/270' target='_blank'>View Comment</a>