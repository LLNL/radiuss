---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-02-13
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5734
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5734' target='_blank'>flux-framework/flux-core#5734</a>.

<p>nodes are drained when a user aborts a run request with prolog running</p><small>Problem: if a user gets impatient while running `flux allooc` or `flux run` and aborts the command while the prolog is running, that causes a SIGTERM to be sent to the prolog which causes it to fail, which drains the node....</small><a href='https://github.com/flux-framework/flux-core/issues/5734' target='_blank'>View Comment</a>