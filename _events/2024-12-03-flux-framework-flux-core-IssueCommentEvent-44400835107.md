---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-12-03
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6466
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6466' target='_blank'>flux-framework/flux-core#6466</a>.

<small>Looking it over, if the calls from job-manager can become a jobtap plugin (not sure but it looks like it at first glance), that would definitely help.  The main thing that might need some thought is how to define "busy" and "quiescent" callbacks in fluxion after everything went asynchronous.  It's not quite as easy as it used to be (we used to just process everything in-order, so when the callback ran, it was time) but now it will have to detect when the sched loop has no further work to do.  That's actually possible, it puts the event loop to sleep in that case until something comes in, but it's a bit more work.  There are also some strange states we didn't really have before, like there being jobs that are satisfiable but not reservable....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6466' target='_blank'>View Comment</a>