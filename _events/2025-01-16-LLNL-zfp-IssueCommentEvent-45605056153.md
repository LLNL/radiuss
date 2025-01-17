---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2025-01-16
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/244
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/244' target='_blank'>LLNL/zfp#244</a>.

<small>@kminemur Thanks for letting us know.  The "failing" tests are the C tests that depend on CMocka and which are not being built, as that requires permission to make symlinks on Windows (see, e.g., https://stackoverflow.com/questions/61243174/replacement-of-create-symlink-in-windows).  These tests pass on the `develop` branch, which uses CMocka 1.1.5, while the `staging` branch uses the most recent version, CMocka 1.1.7.  As I can reproduce this issue on my Windows machine, I will look into what needs to be done to get these tests built on Windows....</small>

<a href='https://github.com/LLNL/zfp/issues/244' target='_blank'>View Comment</a>