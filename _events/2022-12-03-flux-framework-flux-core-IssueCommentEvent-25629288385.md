---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-12-03
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/4794
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/4794' target='_blank'>flux-framework/flux-core#4794</a>.

<small>My guess is that the `ubuntu-latest` tag was updated to 22.04 today, precipitating the failures in the python linting and the system coverage builds (I guess docker-run-systest.sh doesn't work on ubuntu 22.04). I'll update this PR to revert both builders to `ubuntu-20.04`....</small>

<a href='https://github.com/flux-framework/flux-core/pull/4794' target='_blank'>View Comment</a>