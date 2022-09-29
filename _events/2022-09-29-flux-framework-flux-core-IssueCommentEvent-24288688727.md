---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-09-29
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/4623
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/4623' target='_blank'>flux-framework/flux-core#4623</a>.

<small>I was originally thinking something like that, but the function @grondo reminded me of above lets us get a file descriptor that represents “ready” for an entire handle when it shows ready. So we can add the entire handle as a watcher on the loop’s handle with a callback that runs a once-through on its reactor, I think. If that works then we won’t have to worry about it in the loop at all, just ensure that the futures register themselves correctly before yielding. That would mean even communicating with separate flux instances in the same loop should work....</small>

<a href='https://github.com/flux-framework/flux-core/pull/4623' target='_blank'>View Comment</a>