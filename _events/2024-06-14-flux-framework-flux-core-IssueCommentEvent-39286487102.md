---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-06-14
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6040
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6040' target='_blank'>flux-framework/flux-core#6040</a>.

<small>Re-pushed with a templated unit file, `housekeeping@jobid`.  It sets FLUX_JOB_ID but nothing else from the environment of the caller.  I was able to configure it to automatically garbage collect, so when you do `systemctl status housekeeping@*` you only see what's currently running (not past failed units).  `journalctl -u housekeeping@*` works too....</small>

<a href='https://github.com/flux-framework/flux-core/pull/6040' target='_blank'>View Comment</a>