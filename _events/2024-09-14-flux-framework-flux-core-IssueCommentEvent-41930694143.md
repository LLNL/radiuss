---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-09-14
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6283
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6283' target='_blank'>flux-framework/flux-core#6283</a>.

<small>The thing that's bugging me about this solution is it adds a synchronous RPC (as well as a `flux_open()` / `flux_close()` to the parent broker on every rank.  They will go in parallel so it will scale but it adds a fixed startup latency to every job....</small>

<a href='https://github.com/flux-framework/flux-core/pull/6283' target='_blank'>View Comment</a>