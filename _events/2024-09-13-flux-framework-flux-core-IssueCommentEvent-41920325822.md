---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-09-13
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/3927
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/3927' target='_blank'>flux-framework/flux-core#3927</a>.

<small>Yeah, OpenMPI should work, but if we want the library to be loaded we would have to bind mount it into the container and do a great deal of extra intrusive work to do that. Even domain sockets would need to be bind mounted in, but at least wouldn’t require injecting a library that may or may not be compiled with a compatible libc....</small>

<a href='https://github.com/flux-framework/flux-core/issues/3927' target='_blank'>View Comment</a>