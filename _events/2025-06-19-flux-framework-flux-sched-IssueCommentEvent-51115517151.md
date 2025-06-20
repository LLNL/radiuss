---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-06-19
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/986
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/986' target='_blank'>flux-framework/flux-sched#986</a>.

<small>Not substantively, we operate on the IDs as logical IDs (effectively assuming, in absence of actual structure, that lower IDs are close to other lower IDs).  We still have a direct hwloc reader, which I believe is still tested, though we're not currently using it.  We would still need a way to connect the two together.  Really what would likely be most useful in the short term would be to ensure that those logical IDs are translated back to physical IDs in exec or the shell.  Having the actual locality in fluxion would definitely be good, but with what @ryanday36 showed in the issue description just doing that logical->physical translation even with `hwloc-calc` right before doing the env var assignment would fix it.  Admittedly not fix it the long-term "right" way, but we'll need that logical to physical translation anyway because we don't want to be tied to whatever crazy variable numbering cuda or hip use from 1pm to 2pm on alternate Thursdays....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/986' target='_blank'>View Comment</a>