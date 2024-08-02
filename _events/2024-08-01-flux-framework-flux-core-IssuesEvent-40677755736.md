---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-08-01
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6173
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6173' target='_blank'>flux-framework/flux-core#6173</a>.

<p>shell: increase `output.batch-timeout` default for very large jobs</p><small>Problem: In very large jobs (many thousands of job shells) the shell output handling may overwhelm the broker of the enclosing instance with messages. By default, output on each shell rank is batched for 0.5s, so for a job emitting output more quickly than this, this can result in a few thousand messages per second being routed back to the rank running the shell rank 0....</small><a href='https://github.com/flux-framework/flux-core/issues/6173' target='_blank'>View Comment</a>