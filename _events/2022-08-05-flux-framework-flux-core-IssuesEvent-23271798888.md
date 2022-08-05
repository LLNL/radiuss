---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2022-08-05
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4472
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/4472' target='_blank'>flux-framework/flux-core#4472</a>.

<p>broker: content-cache `acct_dirty` can be greater than the number of flushable entries</p><small>While working on #4267, I noticed that sometimes the `acct_dirty` field can be greater than the length of the `flush` list, even when a backing module is not loaded.  a `flux content flush` will therefore hang, b/c `acct_dirty` will never become zero, so the content flush will never respond to the original request....</small><a href='https://github.com/flux-framework/flux-core/issues/4472' target='_blank'>View Comment</a>