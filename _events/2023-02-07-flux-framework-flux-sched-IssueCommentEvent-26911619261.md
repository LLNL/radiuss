---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2023-02-07
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1001
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1001' target='_blank'>flux-framework/flux-sched#1001</a>.

<small>I don't _think_ that could be it.  The accounting scripts communicate with the `job-archive` database and the `mf_priority.so` plugin in the job manager.  But we're seeing fluxion spending lots of time traversing resource graphs while answering feasibility queries at job submission time.  It seems like that wouldn't be affected by say crazy job priorities or even the job manager dealing with an onslaught of messages....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1001' target='_blank'>View Comment</a>