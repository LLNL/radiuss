---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2022-07-20
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/4385
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/4385' target='_blank'>flux-framework/flux-core#4385</a>.

<small>Oh yeah that's my fault. I had told @wihobbs to capture stdout/stderr but add `check=True` because I thought (based on what I read in the docs) it would throw an exception with the captured stderr if the process has a nonzero exit code, but actually the docs say that the exception has the captured stderr as an _attribute_ but it isn't given in the message....</small>

<a href='https://github.com/flux-framework/flux-core/pull/4385' target='_blank'>View Comment</a>