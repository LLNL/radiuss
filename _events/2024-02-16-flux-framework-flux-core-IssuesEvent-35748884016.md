---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-02-16
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5746
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5746' target='_blank'>flux-framework/flux-core#5746</a>.

<p>job shell blocks at exit in degraded job</p><small>Problem: A Flux job can survive loss of a node or job shell if the shell rank does not intersect with the `critical-ranks` set. However, when that job eventually exits "normally" the remaining shells hang at exit, presumably waiting for the lost shell or shells to enter the exit barrier....</small><a href='https://github.com/flux-framework/flux-core/issues/5746' target='_blank'>View Comment</a>