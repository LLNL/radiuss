---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/450194?"
user: gzagaris
date: 2022-12-16
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/issues/798
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/gzagaris' target='_blank'>gzagaris</a> commented on issue <a href='https://github.com/LLNL/Umpire/issues/798' target='_blank'>LLNL/Umpire#798</a>.

<small>Digging a bit deeper and thinking some more about this, I think the fundamental issue is that when the default device allocator is created, Umpire does not take into account whether there is a GPU bound to the current process that the caller has set via `cudaSetDevice` or `hipSetDevice`. ...</small>

<a href='https://github.com/LLNL/Umpire/issues/798' target='_blank'>View Comment</a>