---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2025-05-07
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6802
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6802' target='_blank'>flux-framework/flux-core#6802</a>.

<small>re-pushed, I went with a mildly more complex / sophisticated approach.  Instead of requesting `N` entries from `job-list`, I request `N+1` entries from the `job-list` module.  The length of the returned result is used as "detection" of truncation, and the output warning is output if it is indeed truncated....</small>

<a href='https://github.com/flux-framework/flux-core/pull/6802' target='_blank'>View Comment</a>