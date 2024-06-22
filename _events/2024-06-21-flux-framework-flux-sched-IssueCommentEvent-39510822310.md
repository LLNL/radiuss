---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-06-21
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1222
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>flux-framework/flux-sched#1222</a>.

<small>It isn’t using a batch timer currently, but I’d been considering doing something like that to keep it from spending too long in the actual scheduling loop before re-entering the reactor and it could certainly work here too.  Wouldn’t be too hard to do the other way around. Any idea what makes a good baseline delay or is it too case-specific?  The main potential downside is it will add latency to each job in a slow submission scenario....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>View Comment</a>