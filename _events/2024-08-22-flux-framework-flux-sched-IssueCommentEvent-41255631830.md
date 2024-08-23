---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-08-22
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1171
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1171' target='_blank'>flux-framework/flux-sched#1171</a>.

<small>I have an idea why this might be happening.  Normally first is quick because it considers resources in order, sorted by most available components under them first.  I'm guessing that we consider down nodes to have all their resources available, so even though we quickly skip them we consider them when we shouldn't.  A quick fix for this might be to mark all the resources unavailable when a resource is marked down, or adding up/down as part of the key for that ordered map.  It shouldn't normally make a huge difference, but treating the resources as "allocated" until the end of time in the planner might let us simpllicy some of the logic too. @milroy, you know the planners a whole lot more than I do, can you think of a reason that would cause problems?...</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1171' target='_blank'>View Comment</a>