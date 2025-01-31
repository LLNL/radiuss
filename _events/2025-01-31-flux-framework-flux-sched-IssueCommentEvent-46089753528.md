---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13199119?"
user: wihobbs
date: 2025-01-31
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1268
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/wihobbs' target='_blank'>wihobbs</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1268' target='_blank'>flux-framework/flux-sched#1268</a>.

<small>I think I've incorporated this feedback @trws, though slightly differently than you laid out in your comment. Instead of a `policy` key which accepts `locality`, `variation`, `high`, and `low`, I added a `policy` key that will accept `low` or `high`, and you can still set `match-policy` to `locality`, `variation`, `high`, and `low`, in which case the latter two would result in a "vanilla" `high` or `low` policy without the extra options. Does that suffice for what you laid out? It turned out to be not a huge lift....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1268' target='_blank'>View Comment</a>