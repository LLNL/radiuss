---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2024-08-16
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6222
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6222' target='_blank'>flux-framework/flux-core#6222</a>.

<small>ok, so i don't know why, but there's some subtlety with `FLUX_CONF_DIR=$(pwd) test_must_fail flux core ...` on that one builder.  Perhaps environment not passed through.  Switching to `-o,--config-path=$(pwd)` appears to work around it....</small>

<a href='https://github.com/flux-framework/flux-core/pull/6222' target='_blank'>View Comment</a>