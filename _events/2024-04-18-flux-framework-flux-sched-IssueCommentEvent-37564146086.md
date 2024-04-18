---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-04-18
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1179
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1179' target='_blank'>flux-framework/flux-sched#1179</a>.

<small>Yup, that's exactly what I did was use `git subtree add <path> <uri> --squash` and yes that's what happens is it generates a single commit that contains all the other repository's code and then merges it into the history of the project. It's not something I expect to be terribly common, but it's a nice way to do this kind of thing and have git manage the provenance and updates rather than having to do something like unpack a tarball and add the contents or `git archive | tar x`. As it sits, this and maybe fmt were the only things I thought I might pull in that way, so we might be alright as is if manual merge is alright for a couple of rare one-offs....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1179' target='_blank'>View Comment</a>