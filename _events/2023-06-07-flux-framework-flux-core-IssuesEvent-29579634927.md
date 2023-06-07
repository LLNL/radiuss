---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2023-06-07
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5216
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/5216' target='_blank'>flux-framework/flux-core#5216</a>.

<p>zhashx_insert: cannot return ENOMEM</p><small>While going through #5197 I was surprised to see that `zhashx_insert()`'s comments say it can only return EEXIST on error not ENOMEM.  Looking internally into the code, it appears it `assert()`s on memory errors, thus EEXIST is the only error possible....</small><a href='https://github.com/flux-framework/flux-core/issues/5216' target='_blank'>View Comment</a>