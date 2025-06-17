---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-06-16
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6492
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6492' target='_blank'>flux-framework/flux-core#6492</a>.

<small>I don't recall seeing this when it was being done, but it was mentioned in one of our recent meetings so I came looking. There are at least some updates here, in that uv_ref/unref now exist at least, and the child handling could be handled one of a couple of ways depending on the requirements (either `uv_process_t` if we can, or `uv_signal_t` if not). The others I think are still at least different, and the close item is vaguely interesting, I would think we'd be able to tolerate that even though it is a bit annoying.  It's probably safer for `io_uring` style setups as well as windows, but I'm not 100% sure about that....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6492' target='_blank'>View Comment</a>