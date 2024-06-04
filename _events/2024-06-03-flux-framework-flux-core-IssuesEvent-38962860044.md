---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2024-06-03
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5919
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/5919' target='_blank'>flux-framework/flux-core#5919</a>.

<p>job-exec: possible scaling issue managing many job shells</p><small>I was running a test instance of size=1536 across 32 real nodes, each with 96 cores. When launching 128N/128p jobs there seemed to be some kind of performance issue in job-exec and jobs were not making progress. Perf report shows a lot of time spent in the libsubprocess watchers:...</small><a href='https://github.com/flux-framework/flux-core/issues/5919' target='_blank'>View Comment</a>