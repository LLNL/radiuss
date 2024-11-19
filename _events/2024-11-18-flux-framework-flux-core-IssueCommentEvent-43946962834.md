---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-11-18
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6445
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6445' target='_blank'>flux-framework/flux-core#6445</a>.

<small>I think this would work, but as I look over it I find myself wondering if we might be better off either with a list of things that have been released, or actually leaving this out of hello entirely and using a partial release after the hello response from the scheduler.  The main reason is that this approach sends what is allocated as R, then we have to work out what to release by taking the difference between what is allocated and what needs to be removed before we can act on it.  If instead the released portion is sent, either in hello or as a partial release, we can reuse the same code we already have for partial release without introducing a new code path into what's already proven somewhat complex or fragile. ...</small>

<a href='https://github.com/flux-framework/flux-core/pull/6445' target='_blank'>View Comment</a>