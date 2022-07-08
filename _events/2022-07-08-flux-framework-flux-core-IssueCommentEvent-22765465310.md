---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-07-08
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4325
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4325' target='_blank'>flux-framework/flux-core#4325</a>.

<small>`start failed: flux: No such file or directory` indicates that the job is trying to run the command `flux` and it isn't found in `PATH`. I think the problem is that `flux.job.JobspecV1.from_nest_command()` is created a jobspec with an empty environment by default. Try adding:...</small>

<a href='https://github.com/flux-framework/flux-core/issues/4325' target='_blank'>View Comment</a>