---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-05-30
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/5975
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/5975' target='_blank'>flux-framework/flux-core#5975</a>.

<small>I guess it's a trade off.  The client has turned out to be pretty heavy with the buffering on that end.  OTOH if we buffer on the server end then we can end up with more message framing overhead when there are bursts of messages.  But since it's a common idiom to have many clients in one place spread out across many servers, moving the buffering to the server side probably makes sense....</small>

<a href='https://github.com/flux-framework/flux-core/pull/5975' target='_blank'>View Comment</a>