---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-02-28
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1352
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1352' target='_blank'>flux-framework/flux-sched#1352</a>.

<small>@milroy here's the [commit](https://github.com/flux-framework/flux-sched/pull/1345/commits/9304ad91ec445e5654a79d5367bfe08b7ea1e11f) in #1345 that handles the `shrink` key in the resource acquisition protocol response. Note that `shrink` ranks will also be in the `down` key, so that commit also does some work to create a down-but-not-lost idset (which in the current case will always be empty), since it didn't make sense to mark nodes down then lost. Perhaps the same approach works here to avoid marking ranks down only to remove them....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1352' target='_blank'>View Comment</a>