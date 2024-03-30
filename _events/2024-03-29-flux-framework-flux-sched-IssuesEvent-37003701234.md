---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/165410477?"
user: adamdbertsch
date: 2024-03-29
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1159
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/adamdbertsch' target='_blank'>adamdbertsch</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/1159' target='_blank'>flux-framework/flux-sched#1159</a>.

<p>job submissions are serialized and not interactively performant</p><small>Job submissions are serialized across a large system, and each job submission takes order 10s to complete.  This means that submitting more than a handful of jobs can take minutes, and all other users are blocked from submitting their own jobs during this time.  ...</small><a href='https://github.com/flux-framework/flux-sched/issues/1159' target='_blank'>View Comment</a>