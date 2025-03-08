---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-03-07
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1358
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/1358' target='_blank'>flux-framework/flux-sched#1358</a>.

<p>remove use of `nodes_up` in favor of using the aggregate counts</p><small>This is, as far as I know, only used in the `request_feasibility` check I added not too long ago. It managed to get out of sync due to a bug in update that @milroy recently found, and should be removed so we can have less caches to worry about.  My current thought is we should make it a method and in there use the aggregate filter to get the count, that way if we pivot on it later we can avoid having to track it down again....</small><a href='https://github.com/flux-framework/flux-sched/issues/1358' target='_blank'>View Comment</a>