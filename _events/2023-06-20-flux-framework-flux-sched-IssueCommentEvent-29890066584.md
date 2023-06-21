---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-06-20
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/808
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/808' target='_blank'>flux-framework/flux-sched#808</a>.

<small>The post-mortem here is that somehow we have been ending up with the ppc64le build linking two unwinding implementations at the same time, both libstdc++ and libunwind, and they're slicing each other.  I haven't explicitly checked if this is continuing, but best as I can tell it's an issue caused by the way one of our dependencies is being built....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/808' target='_blank'>View Comment</a>