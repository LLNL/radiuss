---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-07-21
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/4385
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/4385' target='_blank'>flux-framework/flux-core#4385</a>.

<small>It was actually the `el8 - system,coverage` build that timed out. I have noticed that today on my builds as well. It just seems that the coverage builds are taking a lot longer today. I did recently update the `el8` base docker image, so that could have something to do with it, though since both coverage builds are affected in my experience, it could be something else. Coverage does slow everything down since it has to write the gcno/gcda files while running, so maybe we've found a new race or things are just slow....</small>

<a href='https://github.com/flux-framework/flux-core/pull/4385' target='_blank'>View Comment</a>