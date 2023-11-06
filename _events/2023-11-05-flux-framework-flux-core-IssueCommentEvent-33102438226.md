---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2023-11-05
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5532
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5532' target='_blank'>flux-framework/flux-core#5532</a>.

<small>I had to look back at the implementation, but the purpose of `FLUX_TERMINUS_SESSION` is to prevent "nesting" pty sesssions, since the "commands" sent to the server can't be relayed to the deepest nested session. I have to think (and experiment) if the `FLUX_TERMINUS_SESSION` should or should not be set for tasks without a pty, since there is a terminus "server" started for every job (which kind of acts like a tmux server and would techincally let you "attach" an interactive shell to any job)...</small>

<a href='https://github.com/flux-framework/flux-core/issues/5532' target='_blank'>View Comment</a>