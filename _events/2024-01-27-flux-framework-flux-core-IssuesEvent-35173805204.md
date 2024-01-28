---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-01-27
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5709
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5709' target='_blank'>flux-framework/flux-core#5709</a>.

<p>discussion: go bindings for flux-core</p><small>As we are planning on integrating flux better with Kubernetes, it would be nice to have flux-core expose Go bindings. As an example, the approach I'm taking now to expose a flux instance via a service -> ingress -> API that can be interacted with externally is via [a sidecar in the main broker pod](https://github.com/flux-framework/flux-operator/tree/test-refactor-modular/examples/services/sidecar/flux-restful) that is exposed via a port. This means having one physical node with one pod, and within the pod, two containers - one running an interactive flux cluster (it starts up and basically sleeps forever until we are done) and the second running the restful service (they share a common volume that has the flux socket so the second container can connect to it, see the queue, submit jobs, etc)....</small><a href='https://github.com/flux-framework/flux-core/issues/5709' target='_blank'>View Comment</a>