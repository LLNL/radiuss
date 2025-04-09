---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2025-04-07
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6735
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6735' target='_blank'>flux-framework/flux-core#6735</a>.

<small>Well, it's just a heuristic for performance so maybe the answer is to add a comment to the places where it's used to explain that?   As you suggest, maybe instead of testing against BLOBREF_MAX_STRING_SIZE in two places, we should add a convenience function to libkvs like `bool treeobj_value_is_small (size_t size)` that can be used instead?...</small>

<a href='https://github.com/flux-framework/flux-core/issues/6735' target='_blank'>View Comment</a>