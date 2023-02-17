---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2023-02-16
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4943
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/4943' target='_blank'>flux-framework/flux-core#4943</a>.

<p>libsubprocess leaks private symbols</p><small>Problem: some internal functions in libsubprocess have a `flux_` prefix which allows makes them available publicly (with no installed header)  when libsubprocess is incorporated into `libflux-core.so`.