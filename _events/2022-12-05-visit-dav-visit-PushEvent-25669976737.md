---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2022-12-05
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/a1b3860030bbbe4dcb693997e247cd7d98b0ee87
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Rm bizarre last line (#18348) (#18349)

The last line had no effect because the `exec` statements in both branches of the `if-else` block meant it was never executed. On top of that, there is no clear idea what that line was *intended* to do. What it did do was call `frontendlauncher` (`$0`) recursively with three args, `=`, `shift` and `@ARGV;` which I think was not intentional.</small>

<a href='https://github.com/visit-dav/visit/commit/a1b3860030bbbe4dcb693997e247cd7d98b0ee87' target='_blank'>View Commit</a>