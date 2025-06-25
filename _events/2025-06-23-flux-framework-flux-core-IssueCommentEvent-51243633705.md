---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-06-23
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6886
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6886' target='_blank'>flux-framework/flux-core#6886</a>.

<small>Ok, I was able to reproduce this in the unit tests. Looks like this was an issue with a missing `+` in front an `=` when handling increment of a `struct tm` `tm_wday` member 🤦, at least this patch fixes the hang as it is reproduced:...</small>

<a href='https://github.com/flux-framework/flux-core/issues/6886' target='_blank'>View Comment</a>