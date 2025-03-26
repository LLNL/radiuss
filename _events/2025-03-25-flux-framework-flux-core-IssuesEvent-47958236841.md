---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2025-03-25
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6709
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/6709' target='_blank'>flux-framework/flux-core#6709</a>.

<p>job-info: cancellation lists do not scale well</p><small>Very similar to #6695, the loops in `watchers_cancel()` and `guest_watchers_cancel()` (edit: and probably update watchers cancel), which iterate through all current watchers can be slow and scale poorly....</small><a href='https://github.com/flux-framework/flux-core/issues/6709' target='_blank'>View Comment</a>