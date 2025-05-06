---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-05-05
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6796
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6796' target='_blank'>flux-framework/flux-core#6796</a>.

<p>wait for housekeeping on normal shutdown</p><small>During shutdown, Flux waits for all queues to be idle via `flux queue idle --quiet` (which is the final command pushed into the broker "cleanup" stack via `flux admin cleanup-push` in the default `rc1`). However, it doesn't appear that Flux waits for subsequent housekeeping work to complete if there is any active housekeeping or if any housekeeping was started from the cancellation of running jobs during shutdown....</small><a href='https://github.com/flux-framework/flux-core/issues/6796' target='_blank'>View Comment</a>