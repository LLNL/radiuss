---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2022-06-23
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/946
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/946' target='_blank'>flux-framework/flux-sched#946</a>.

<p>Dynamic restrictions on job resource placement</p><small>Following up on a coffee hour discussion with @grondo and @milroy , when users request persistent rabbit allocations which are independent of compute node jobs, users will need to be able to submit jobs which can use the rabbit allocation. For Lustre allocations, which communicate with compute nodes over the network, this introduces no issues. But when persistent rabbit allocations are for one of the rack-local/PCIe-connected file system types (GFS2, XFS, raw), any job which requests to use the allocation will need to have nodes chosen for it in a way that matches up with the rabbit allocation (e.g. a certain number of nodes per rack on specific racks)....</small><a href='https://github.com/flux-framework/flux-sched/issues/946' target='_blank'>View Comment</a>