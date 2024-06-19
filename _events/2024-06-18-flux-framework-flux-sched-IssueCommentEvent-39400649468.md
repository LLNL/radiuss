---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-06-18
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1222
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>flux-framework/flux-sched#1222</a>.

<small>At least it finishes I guess. I had a test where one out of say 3 runs just bulk submitting 100 jobs asking for the same drained node, then two jobs asking for 1 node (no requirement) would actually hang after scheduling the first 3-5 jobs. The cancels probably provide the necessary trips back into the scheduling loop, though that performance is just horrendous. I have a couple of things stacked up to help that somewhat. Hoping maybe we can work it so that a cancel can apply to an in-progress scheduling loop. I think I can make that safe, possibly without even restarting it. ...</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1222' target='_blank'>View Comment</a>