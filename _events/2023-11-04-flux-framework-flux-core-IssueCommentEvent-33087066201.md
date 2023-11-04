---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2023-11-04
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5530
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5530' target='_blank'>flux-framework/flux-core#5530</a>.

<small>Hmm, maybe we could have the broker and flux-proxy both store the owner userid in an environment variable like FLUX_OWNER.  Then the connector could use SO_PEERCRED to get the peer pid.  If the peer uid matches getuid() then pull FLUX_OWNER out of the peer pid's environment and check that?...</small>

<a href='https://github.com/flux-framework/flux-core/issues/5530' target='_blank'>View Comment</a>