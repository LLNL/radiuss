---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2023-02-07
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4921
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4921' target='_blank'>flux-framework/flux-core#4921</a>.

<small>FWIW this avoid the problem for `flux start`, but it relies on the fact that `kvsname` would be set to a non empty string in every other case where libpmi is used.  I'm not sure if that's true for cray or true generally.  It would probably be good to get a bug open with cray to see if they can do something different in their `PMI_KVS_Get()` when singleton mode (e.g. return an error instead of spinning)....</small>

<a href='https://github.com/flux-framework/flux-core/issues/4921' target='_blank'>View Comment</a>