---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2022-11-17
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4629
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4629' target='_blank'>flux-framework/flux-core#4629</a>.

<small>I haven't looked in detail yet (and may not get to for a bit) but I would say that a goal  for now should be to touch the alloc.c code as little as possible since that code is critical and this feature is not a really high priority AFAIK.  If we can build the new functionality into queue.c and just add a few helpers in alloc.c, that would be ideal.  I am fine with moving the admin RPC out of alloc.c though....</small>

<a href='https://github.com/flux-framework/flux-core/issues/4629' target='_blank'>View Comment</a>