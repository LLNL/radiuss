---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-02-23
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1001
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1001' target='_blank'>flux-framework/flux-sched#1001</a>.

<small>Wow, almost no impact to negative impact.  That's unfortunate, but really good to know.  I found some things, thanks to help from @grondo, that might be impacting us from the Constraints.  Once that bug is squashed we can take another pass on the performance.  I'm guessing we're not getting a win from the unordered maps because of the hashing cost, which we could fix with pre-hashed strings or interned strings, might be worth doing the string rework and then circling back to the data types, even if that's more painful. =/...</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1001' target='_blank'>View Comment</a>