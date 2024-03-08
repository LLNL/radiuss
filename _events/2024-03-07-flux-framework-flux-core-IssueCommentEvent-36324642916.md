---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/862123?"
user: dongahn
date: 2024-03-07
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4312
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/dongahn' target='_blank'>dongahn</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4312' target='_blank'>flux-framework/flux-core#4312</a>.

<small>I quickly reviewed the fluxion code, and the change seems manageable. Setting aside the work on qmanager, the fluxion-resource service takes care of deallocating resources by traversing the resource tree with the jobid and removing allocations tagged with that jobid. A viable strategy could involve taking the R fragment during the removal process and deallocating only the resources that the R fragment covers. I can provide more guidance on this task if needed. The ability to return resources partially in large-scale systems is crucial. I can look some more over the weekend and add more suggestions....</small>

<a href='https://github.com/flux-framework/flux-core/issues/4312' target='_blank'>View Comment</a>