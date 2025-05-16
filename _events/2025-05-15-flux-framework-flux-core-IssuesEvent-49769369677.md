---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-05-15
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6820
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6820' target='_blank'>flux-framework/flux-core#6820</a>.

<p>feature: freeze system instance jobs</p><small>In some situations, such as a power demand event, it may be useful to pause a set of jobs on the system. Since system instance jobs are running as transient systemd units, one method to do this would be to use the freezer cgroup to suspend and resume all tasks in the job as a group. In fact, to suspend all tasks for all jobs it may be possible to "freeze" the `flux` user slice as a whole....</small><a href='https://github.com/flux-framework/flux-core/issues/6820' target='_blank'>View Comment</a>