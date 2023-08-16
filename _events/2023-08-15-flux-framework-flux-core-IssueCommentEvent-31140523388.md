---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13872149?"
user: watson6282
date: 2023-08-15
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5391
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/watson6282' target='_blank'>watson6282</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5391' target='_blank'>flux-framework/flux-core#5391</a>.

<small>Correct.  We still require a manual `nodeup` to start the flux broker (and other stuff) after a node reboot.  It takes over ten minutes for a node to reboot back to a point where `nodeup` can be run.  I'm assuming that is long enough for the epilog-running process to complete and drain these down nodes.  We are also very unlikely to `nodeup` nodes that don't have a drain message....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5391' target='_blank'>View Comment</a>