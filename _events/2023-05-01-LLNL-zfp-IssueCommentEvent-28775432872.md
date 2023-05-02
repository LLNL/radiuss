---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-05-01
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/205
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/205' target='_blank'>LLNL/zfp#205</a>.

<small>It appears that you're compiling zfp in C89 mode but the compiler presumably uses the LLP64 data model, which zfp is not detecting correctly (testzfp reports "data model unknown").  One thing to try is to add the following to the CMake line:...</small>

<a href='https://github.com/LLNL/zfp/issues/205' target='_blank'>View Comment</a>