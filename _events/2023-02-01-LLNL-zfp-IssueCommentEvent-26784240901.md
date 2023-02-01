---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-02-01
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/199
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/199' target='_blank'>LLNL/zfp#199</a>.

<small>Doing some more research, it appears that ThreadSanitizer is to blame.  It throws false positives on OpenMP code that *clearly* is thread safe.  For instance, on the example from #198, ThreadSanitizer flags a line a code *within* the critical region as a data race, which obviously is nonsensical....</small>

<a href='https://github.com/LLNL/zfp/issues/199' target='_blank'>View Comment</a>