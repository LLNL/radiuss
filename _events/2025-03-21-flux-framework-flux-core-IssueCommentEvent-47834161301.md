---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2025-03-21
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6715
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6715' target='_blank'>flux-framework/flux-core#6715</a>.

<small>yeah, when i discovered it I realized "oh crap, we could improve performance by NOT canceling watchers" .... to some loose extent the work to solve #6695 and #6709 made two iterations over watchers into 1 iteration.  Since the update watcher for R in the job-shell was only doing 1 iteration to begin with, the addition of the cancel actually was a net loss....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6715' target='_blank'>View Comment</a>