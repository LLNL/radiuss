---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2025-04-16
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6769
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6769' target='_blank'>flux-framework/flux-core#6769</a>.

<small>I think this was a technique to avoid a copy in what I thought might be a performance critical section.  But don't we complete the transaction before the message is destroyed (upon return of the message handler callback)?  Is the problem just that we don't clear it so if we don't overwrite all the fields next time there remain danglers?...</small>

<a href='https://github.com/flux-framework/flux-core/issues/6769' target='_blank'>View Comment</a>