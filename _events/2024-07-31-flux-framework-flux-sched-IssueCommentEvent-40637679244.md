---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-07-31
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/938
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/938' target='_blank'>flux-framework/flux-sched#938</a>.

<small>We use jansson in sched currently, though we’ll probably use boost json or similar in some places in the future which does also support it so that’s not the part I’m most worried about. That said json itself does not, and that includes the json libraries we use in python and lua. Python’s built in main lib dies if you try to give it a 64bit int from numpy or ctypes, and some of our supported lua versions can’t represent a 64 bit int natively to begin with because they also only support double (all below 5.3). Unless we want to play whack-a-mole with all the language integrations and possible json encoding issues, we should really limit ourselves to numbers precisely representable as doubles or send them as strings....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/938' target='_blank'>View Comment</a>