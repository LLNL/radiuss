---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-03-18
repo_name: LLNL/merlin
html_url: https://github.com/LLNL/merlin/issues/406
repo_url: https://github.com/LLNL/merlin
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/LLNL/merlin/issues/406' target='_blank'>LLNL/merlin#406</a>.

<small>The docker-compose example should work! For testing I'm just spinning up redis locally, but for the Flux Operator we have separate containers that provide services: https://flux-framework.org/flux-operator/tutorials/services.html. There are two modes (and likely I'll test and think about both). For one - the service is provided as a sidecar container. So an indexed job with N containers running merlin would have one sidecar per container. That wouldn't be ideal if all nodes running merlin (via flux) need access to the same database. The second design (which I haven't tested yet, but technically it's simpler than the above) is to bring up a single (shared) service for all the worker nodes to access. Glancing at these files, the hardest thing (for the Flux Operator) will be to generate the shared config files and volumes in advance. Likely I'll just do this manually for now and make a tutorial, but (if you like this idea generally) this could be an opportunity to make a simple Kubernetes operator just for running these merlin workflows. They are fairly fun to make! I'm also thinking about if it might be possible to have the concept of a Flux Operator plugin - e.g., adding an ability to use "Flux Operator + Merlin" and then having some of the complexity handled by the plugin. I'll do more research/reading about this today - editing audio first but should have some time later....</small>

<a href='https://github.com/LLNL/merlin/issues/406' target='_blank'>View Comment</a>