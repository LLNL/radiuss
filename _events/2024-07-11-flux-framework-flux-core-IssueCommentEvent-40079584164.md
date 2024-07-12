---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/39344343?"
user: ryanday36
date: 2024-07-11
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6091
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/ryanday36' target='_blank'>ryanday36</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6091' target='_blank'>flux-framework/flux-core#6091</a>.

<small>The goal is to add up the resource usage of all of a users running jobs and prevent them from starting a new job if their resource usage would exceed some limit. The approach that Mark is suggesting sounds like it would work in most cases. In principle a user could exceed the limit by submitting some jobs that only specify nodes and others that only specify cores, but that would probably be rare in practice. Another possible place where these limits wouldn't work would be jobs that specify a number of cores that isn't an even multiple of the number of cores per node on node exclusive clusters, as it sounds like those jobs will effectively reserve more cores than the `ncores` in the jobspec. Once again though, I don't know how common that scenario actually is in practice. The most common case for this is probably `-n 1`, and we could pick that up easily by always assuming a running job is using at least one node, but I could also see someone submitting a bunch of `-n 40` jobs on a cluster with 36 cores per node and getting many more jobs than the limit because those aren't being as using 72 cores....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6091' target='_blank'>View Comment</a>