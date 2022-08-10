---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2022-08-09
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4482
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/4482' target='_blank'>flux-framework/flux-core#4482</a>.

<p>broker: content-cache flush list can be corrupted</p><small>While working on #4267 I saw `flux content flush` hang during some regression tests.  Debugging I eventually realized that the `acct_dirty` in the `content-cache` and the length of the flush list were not consistent.  With `acct_dirty` never reaching zero, `flux content flush` would hang never getting a reply....</small><a href='https://github.com/flux-framework/flux-core/issues/4482' target='_blank'>View Comment</a>