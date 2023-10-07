---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13199119?"
user: wihobbs
date: 2023-10-06
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5491
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/wihobbs' target='_blank'>wihobbs</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5491' target='_blank'>flux-framework/flux-core#5491</a>.

<small>Ahh, I see what you mean. The "limited" `JobInfo` argument isn't playing nice with the `to_dict()` call in the `JobInfo` class. See [/src/bindings/python/flux/job/info.py line 520](https://github.com/flux-framework/flux-core/blob/10abbf4d3aa9943ea617837043f5e003ef8e1de7/src/bindings/python/flux/job/info.py#L544) -- all the properties are explicitly defined (in line 305) on the assumption that the JobInfo class is complete. But having access to that API call with `JobInfo` returned from `result` or `result_async` would be helpful (although there are other ways to get the info, too)....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5491' target='_blank'>View Comment</a>