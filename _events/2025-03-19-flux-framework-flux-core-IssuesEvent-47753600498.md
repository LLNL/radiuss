---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2025-03-19
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6695
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/6695' target='_blank'>flux-framework/flux-core#6695</a>.

<p>kvs-watch: loop in watch_cancel_all() does not scale well</p><small>Per some profiling done following up #6690 and #6694 work, if kvs-watch is being used by a lot of jobs (i.e. lots of namespaces), the loop in `watch_cancel_all()` does not scale well after every call to cancel a watcher.  i.e. the loop is regularly iterating on every namespace that it is watching and every request within each of those namespaces.  This leads to a slowdown in processing and eventually the ENODATA that is sent to the original watcher....</small><a href='https://github.com/flux-framework/flux-core/issues/6695' target='_blank'>View Comment</a>