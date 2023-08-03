---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2023-08-02
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1050
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-sched/issues/1050' target='_blank'>flux-framework/flux-sched#1050</a>.

<p>config.h is missing from source code</p><small>Problem: as noted in flux-framework/flux-accounting#365, `config.h` is not included in many of the cpp source modules. It's a good practice in autotools projects to include that right at the top of all (non-vendored) `.c` and `.cpp` source files, immediately following the copyright header, e.g....</small><a href='https://github.com/flux-framework/flux-sched/issues/1050' target='_blank'>View Comment</a>