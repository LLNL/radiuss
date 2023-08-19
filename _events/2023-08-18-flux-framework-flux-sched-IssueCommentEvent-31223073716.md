---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-08-18
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/989
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/989' target='_blank'>flux-framework/flux-sched#989</a>.

<small>It's possible that the warning suppression was in a header surrounding that include before, or that something else was suppressing it.  I can fix this more correctly in the cmake PR, if you would please mark a TODO to fix it in the automake file, and add the `-Wno-error=missing-template-keyword' to the CXXFLAGS for the appropriate file or files, that will get this done so we can make yggdrasil a system include in the other one (system includes don't get warning checked by default, there are boost issues in this class too, that's why I ended up going down the cmake rabbit hole in the first place)....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/989' target='_blank'>View Comment</a>