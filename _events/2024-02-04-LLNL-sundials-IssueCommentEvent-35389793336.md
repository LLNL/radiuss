---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2073427?"
user: s-u
date: 2024-02-04
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/409
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/s-u' target='_blank'>s-u</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/409' target='_blank'>LLNL/sundials#409</a>.

<small>To be more specific here (and not rely on external links) - in several places the sundials C code assumes that the `long` type is a 64-bit integer type, however, that assumption is wrong. The C standard defines the `long` type as at least 32-bit and on Windows it is exactly 32-bit. Above are some instances listed where 64-bit constants are cast to `unsigned long` and thus truncated to 32-bit, but generally, there are more places in the code where the `long` type is used incorrectly....</small>

<a href='https://github.com/LLNL/sundials/issues/409' target='_blank'>View Comment</a>