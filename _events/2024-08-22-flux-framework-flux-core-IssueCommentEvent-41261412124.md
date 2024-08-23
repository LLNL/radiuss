---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2024-08-22
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6217
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6217' target='_blank'>flux-framework/flux-core#6217</a>.

<small>> I could be wrong but it seems like, for transactional consistency, the delete of the placeholder must go through the journal if the journal is active, but if the file system is full, that would fail. If you close the database, the close ought to try to flush the journal backlog, but of course that will fail if you can't delete the placeholder....</small>

<a href='https://github.com/flux-framework/flux-core/pull/6217' target='_blank'>View Comment</a>