---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2023-10-30
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1103
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/1103' target='_blank'>flux-framework/flux-sched#1103</a>.

<p>fluixion assigns jobs requesting unlimited duration an expiration time >  instance expiration</p><small>Problem: when a job is submitted with unlimited duration, fluxion assigns it an expiration time that is (start time + instance duration), which does not account for the time elapsed between instance start and job start.  As a result, the job's expiration time is after the instance is no longer running....</small><a href='https://github.com/flux-framework/flux-sched/issues/1103' target='_blank'>View Comment</a>