---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-06-23
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/384
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/384' target='_blank'>flux-framework/flux-core#384</a>.

<small>Also thought I'd note here that glibc `posix_spawn(3)` doesn't seem to use `vfork(2)` (or rather, vfork-like clone flags) on TOSS 3 in my experiments. My only clue is that there was no equivalent spawn speedup on this system with the exact same experimental code changes (and `perf` reported a lot of time spent copying page tables)....</small>

<a href='https://github.com/flux-framework/flux-core/issues/384' target='_blank'>View Comment</a>