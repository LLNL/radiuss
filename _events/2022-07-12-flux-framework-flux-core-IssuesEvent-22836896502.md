---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2022-07-12
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/384
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/384' target='_blank'>flux-framework/flux-core#384</a>.

<p>Optionally use posix_spawn(3) instead of fork/exec in libsubprocess</p><small>While this is not an immediate priority, forking overhead in the broker is non-negligible, both in subprocess and wreck.  In some of my tests I'm hitting >= 40% of the broker time spent copying its page-tables.  This seems to be a result of a combination of things:...</small><a href='https://github.com/flux-framework/flux-core/issues/384' target='_blank'>View Comment</a>