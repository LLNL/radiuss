---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-08-06
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1262
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1262' target='_blank'>flux-framework/flux-sched#1262</a>.

<small>Ok, took a bit of non-trivial digging to work out how to address the original issue here.  The first version worked great on all current-gen compilers, and failed on anything even vaguely behind.  It was all non-determinism in cleanup of statics.  Making that all work when the backing store and the strings themselves need to be able to have static or non-static lifetime took a little bit of reworking.  To explain what's going on a little bit for posterity and reviewers:...</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1262' target='_blank'>View Comment</a>