---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-04-21
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1029
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1029' target='_blank'>flux-framework/flux-sched#1029</a>.

<small>Ok, I need to look into the actual source to try to fix this the right way, but for this purpose it looks like a new warning tripping on werror. It’s detecting something as maybe-uninitialized and bailing out, so -Wno-error=maybe-uninitialized or just -Wno-error should pass this. We should turn that off for distribution packaging anyway rather than breaking our packages on new compilers by default, but I’m not sure there’s a great way to do that but have it on by default during development....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1029' target='_blank'>View Comment</a>