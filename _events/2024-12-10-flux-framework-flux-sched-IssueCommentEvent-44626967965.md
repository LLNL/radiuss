---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-12-10
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1319
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1319' target='_blank'>flux-framework/flux-sched#1319</a>.

<small>That's pretty much what I would have expected to happen.  I'm sure we can fix this, but as it sits we don't just validate it, the queue is the actual object in qmanager that defines behavior for various transitions, there's no notion of a job that doesn't have a queue so there are a number of places where we unconditionally invoke something on the queue of a job....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1319' target='_blank'>View Comment</a>