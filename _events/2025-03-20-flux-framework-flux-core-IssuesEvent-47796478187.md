---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2025-03-20
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6304
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/6304' target='_blank'>flux-framework/flux-core#6304</a>.

<p>set `exit-timeout=none` for `flux batch` and `flux alloc` jobs</p><small>Flux instances as jobs have a certain level of resilience -- they can lose compute nodes that are leaves in the TBON and will not be terminated. The idea here is that the node failure _within_ the batch/alloc job will terminate any job using that node. If the instance was running just one full-size job, then termination of that job will cause the batch script to exit and the instance will terminate. If the instance is running SCR or has many small jobs, though, it can continue to get work done....</small><a href='https://github.com/flux-framework/flux-core/issues/6304' target='_blank'>View Comment</a>