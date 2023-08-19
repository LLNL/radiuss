---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-08-18
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/5393
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/5393' target='_blank'>flux-framework/flux-core#5393</a>.

<small>> Now, to your question about whether we could use the current logic... yes, we could find a way to do that. We'd need to, when the class is created or on first call, have it generate a FunctionWrapper instance for each of the functions. They could be simplified slightly since they're being called in a known way, but then each call would basically be self._<memberFunctionWrapper>(args...). ...</small>

<a href='https://github.com/flux-framework/flux-core/pull/5393' target='_blank'>View Comment</a>