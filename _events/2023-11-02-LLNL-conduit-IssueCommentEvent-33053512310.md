---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/971921?"
user: ibaned
date: 2023-11-02
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1185
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/ibaned' target='_blank'>ibaned</a> commented on issue <a href='https://github.com/LLNL/conduit/issues/1185' target='_blank'>LLNL/conduit#1185</a>.

<small>Ah, that's unfortunate... Even if you went through the refactoring to put those commands there and change the paths it would likely break current users who find the top-level `CMakeLists.txt` file in `src`... I suppose this is something that would be compatibility breaking so it's up to you if you want to go through the trouble. We can keep working around it, but at least if you start future projects it would be great to follow the convention of a root directory CMake file. Thanks for trying!...</small>

<a href='https://github.com/LLNL/conduit/issues/1185' target='_blank'>View Comment</a>