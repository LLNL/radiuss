---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-09-19
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/969
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/969' target='_blank'>flux-framework/flux-sched#969</a>.

<small>As came up on slack, we probably should be moving toward int or struct of int representations for time everywhere eventually, but we need to be very careful about the conversions in the interim. One upside to Chrono is we can make a duration of type double representing ints, and safely assign it into a duration wrapping int types of an appropriately finer granularity and not worry about it, but we should probably decide what final representation we want to end up with and use that....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/969' target='_blank'>View Comment</a>