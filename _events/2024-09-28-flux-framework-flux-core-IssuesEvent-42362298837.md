---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-09-28
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6323
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6323' target='_blank'>flux-framework/flux-core#6323</a>.

<p>perilog: rethink sending SIGKILL after SIGTERM when canceling prolog/epilog</p><small>When the perilog plugin cancels the prolog/epilog, it first sends SIGTERM followed by a SIGKILL after a configurable number of seconds. For this use case perhaps the SIGKILL is not necessary, since the administrative prolog/epilog should behave when sent SIGTERM, and begin its termination process (which should be given a longer grace period than the default of 5s)...</small><a href='https://github.com/flux-framework/flux-core/issues/6323' target='_blank'>View Comment</a>