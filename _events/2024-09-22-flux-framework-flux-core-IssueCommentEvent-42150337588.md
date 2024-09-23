---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-09-22
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6294
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6294' target='_blank'>flux-framework/flux-core#6294</a>.

<small>It certainly shouldn't be. The passed function object is called only once.  If there's a way the call from the event loop can be retried, like if it's not reset or something, then it's possible an exception could be causing it to exit before hitting that point and the event loop is re-calling it but it would have to be something like that....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6294' target='_blank'>View Comment</a>