---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-06-21
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1222
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>flux-framework/flux-sched#1222</a>.

<small>I'll open an issue in flux-core to investigate the job-manager sending alloc requests after the jobs have a fatal exception raised, but I wonder if the alloc requests have all already been sent (I think Fluxion uses the `unlimited` alloc limit, so no alloc requests are "held back") and are sitting in the message queue of the qmanager? We could perhaps check if the behavior is duplicated with sched-simple....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>View Comment</a>