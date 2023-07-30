---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2023-07-29
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/5359
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/5359' target='_blank'>flux-framework/flux-core#5359</a>.

<small>I reworked the tests that try to exceed the memory limit so that they can either be killed with SIGKILL (oom) or exit with a code of 1, since either can happen, depending on the value of `vm.memory_overcommit`.  Also they now wait up to 60 seconds to be killed in case the kernel is a little slow....</small>

<a href='https://github.com/flux-framework/flux-core/pull/5359' target='_blank'>View Comment</a>