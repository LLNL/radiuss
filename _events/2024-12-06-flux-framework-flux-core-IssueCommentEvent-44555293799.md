---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2024-12-06
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6456
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6456' target='_blank'>flux-framework/flux-core#6456</a>.

<small>While this issue still exists, it appears that the larger performance issue is in `job-info`, where an entire lookup on the entire key is done if the job has completed.  That should probably similarly be "windowed" as well....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6456' target='_blank'>View Comment</a>