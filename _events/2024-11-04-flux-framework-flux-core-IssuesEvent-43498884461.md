---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-11-04
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6414
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6414' target='_blank'>flux-framework/flux-core#6414</a>.

<p>kvs-watch: avoid re-fetching the same data repeatedly</p><small>Problem: `flux_kvs_lookup(FLUX_KVS_WATCH | FLUX_KVS_WATCH_APPEND)` is implemented inefficiently.  Although it returns only new data that has been appended to a watched key, the `kvs-watch` module internally fetches the entire value each time the key is mentioned in a `kvs.setroot` event, before returning only the data after the watcher's current offset....</small><a href='https://github.com/flux-framework/flux-core/issues/6414' target='_blank'>View Comment</a>