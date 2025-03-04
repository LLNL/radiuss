---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2025-03-04
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6644
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/6644' target='_blank'>flux-framework/flux-core#6644</a>.

<p>job epilog should be able to time out</p><small>Problem: A job epilog (as executed by the `perilog.so` plugin) doesn't currently support a timeout. The [documentation](https://flux-framework.readthedocs.io/projects/flux-core/en/latest/man5/flux-config-job-manager.html#perilog-so) notes that `timeout` and `kill-timeout` are supported for the epilog, but not suggested except for testing (and I can't remember why that is) Furthermore, these values were configured on the affected system and the epilog was not timed out....</small><a href='https://github.com/flux-framework/flux-core/issues/6644' target='_blank'>View Comment</a>