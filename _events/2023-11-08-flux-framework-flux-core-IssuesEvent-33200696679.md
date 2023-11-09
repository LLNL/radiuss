---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/797013?"
user: mattaezell
date: 2023-11-08
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5544
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mattaezell' target='_blank'>mattaezell</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5544' target='_blank'>flux-framework/flux-core#5544</a>.

<p>jansson version requirement on SLES</p><small>`flux-core` requires `jansson` 2.10 (#3240), but SLES provides `jansson` version 2.9 (even sles15-sp5). It looks like you really just needed a feature from 2.8 but selected 2.10 because it is what was in EL7. Would you be willing to relax the version requirement to make SLES packaging easier? It compiles fine against 2.9, and I haven't found any issues in my testing to date. `make check` fails with:...</small><a href='https://github.com/flux-framework/flux-core/issues/5544' target='_blank'>View Comment</a>