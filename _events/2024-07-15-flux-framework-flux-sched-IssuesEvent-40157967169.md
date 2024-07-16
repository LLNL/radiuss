---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-07-15
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1245
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/1245' target='_blank'>flux-framework/flux-sched#1245</a>.

<p>memory leak on status update</p><small>The json_t * variables R_all, R_down and R_alloc in status_request_cb are only freed by `json_decref` on the error path. The caches in the ctx (m_r_{all,down,alloc}) are never freed at all.  Found this thanks to a 10k leak heaptrack found on one of our drained resource tests, tiny in the test, but could get larger over time if there are a lot of requests to this RPC, or a lot of resource updates, or especially both....</small><a href='https://github.com/flux-framework/flux-sched/issues/1245' target='_blank'>View Comment</a>