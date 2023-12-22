---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2023-12-21
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5611
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/5611' target='_blank'>flux-framework/flux-core#5611</a>.

<p>resource: fetch local hwloc topology from enclosing instance</p><small>The job shell fetches hwloc topology XML from the local broker's resource module via the `resource.topo-get` RPC instead of loading the topology XML via `hwloc_topology_load()`. This helps with job throughput since `hwloc_topology_load()` can be very slow, especially when many processes are performing it at the same time, but it also allows the job shell to "see" the same topology as the broker in the case fake resources are loaded....</small><a href='https://github.com/flux-framework/flux-core/issues/5611' target='_blank'>View Comment</a>