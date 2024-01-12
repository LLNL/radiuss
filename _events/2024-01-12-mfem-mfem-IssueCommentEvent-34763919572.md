---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2024-01-12
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4065
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4065' target='_blank'>mfem/mfem#4065</a>.

<small>Yes, it will definitely work with nesting. The first time the operator is applied, you won't see any benefit (since the allocator has to set up the buffers initially), but for subsequent operator applications, the allocations should be essentially free. The memory usage will be the maximum sum of the sizes of temporary vectors that are alive simultaneously....</small>

<a href='https://github.com/mfem/mfem/pull/4065' target='_blank'>View Comment</a>