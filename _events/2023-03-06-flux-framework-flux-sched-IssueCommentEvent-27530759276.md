---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2023-03-06
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1013
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1013' target='_blank'>flux-framework/flux-sched#1013</a>.

<small>I realized the PR will need updating. As it stands the job will never run, because each time qmanager iterates through the jobs and reaches the deferred job it will set the at time to be _**n**_ (`deferred_start`) seconds in the future. We will need to specify `deferred_start` seconds in the future from the time at which the jobspec is first submitted, and then reduce the at time each time qmanager executes a loop....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1013' target='_blank'>View Comment</a>