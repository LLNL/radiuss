---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-03-21
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5811
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5811' target='_blank'>flux-framework/flux-core#5811</a>.

<p>job-exec: job takes longer than necessary to terminate after a node failure</p><small>When the job-exec module handles a node failure on a non-critical rank it raises a job exception but does not also notify the rank 0 job shell that a shell has gone away. This causes the job shell to wait indefinitely in the output plugin for EOF from the missing shell....</small><a href='https://github.com/flux-framework/flux-core/issues/5811' target='_blank'>View Comment</a>