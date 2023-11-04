---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2023-11-03
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/commit/d878c672e6bd668c1423abf94a820218db9a3bda
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> pushed to <a href='https://github.com/flux-framework/flux-core' target='_blank'>flux-framework/flux-core</a>

<small>job-manager: allow duration update of running job

Problem: Adjusting the duration of a running job is currently not
supported, but this would be useful for jobs that are about to exceed
their time limit but have not yet computed the desired result.

Allow updates of duration for running jobs by the instance owner only
in the update-duration plugin. Since the update is being requested
by the instance owner, no validation is required and the new duration
can be set to anything, including unlimited.

Adjust the error message when a user attempts to update the duration
of one of their own running jobs. Fix one test that expects the old
error message.</small>

<a href='https://github.com/flux-framework/flux-core/commit/d878c672e6bd668c1423abf94a820218db9a3bda' target='_blank'>View Commit</a>