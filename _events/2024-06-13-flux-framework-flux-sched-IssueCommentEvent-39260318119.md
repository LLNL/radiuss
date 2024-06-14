---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-06-13
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1222
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>flux-framework/flux-sched#1222</a>.

<small>Oh wow. They died on a cancel from resource.acquire.  I'm actually not sure how we could get to a `FATAL: exception not rethrown` like that, it actually looks like what would happen if you hit an uncaught `throw` inside a destructor and terminated the process.  Did it OOM or something?...</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>View Comment</a>