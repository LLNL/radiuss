---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2022-07-08
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4368
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/4368' target='_blank'>flux-framework/flux-core#4368</a>.

<p>jobtap: replace `job.new` with `job.create`, `job.destroy` and add valid job callback</p><small>As noted in #4366 [this comment]((https://github.com/flux-framework/flux-core/pull/4366#issuecomment-1155229093)), we should replace `job,new` with a `job.create` and `job.destroy` pair. This will give jobtap plugins a place to get notified of all jobs before validation and subscribe to job events, set job defaults, and create job state for jobs even when they might be marked as invalid by another jobtap plugin....</small><a href='https://github.com/flux-framework/flux-core/issues/4368' target='_blank'>View Comment</a>