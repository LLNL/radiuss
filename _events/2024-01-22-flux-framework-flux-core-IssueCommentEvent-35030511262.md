---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-01-22
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5696
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5696' target='_blank'>flux-framework/flux-core#5696</a>.

<small>Ok, the underlying error for the `pty: send data` error is "Invalid UTF-8 string" coming from `json_pack()` or the equivalent underneath `flux_respond_pack()`. I wonder if there is a U+0000 character in the output which jansson is refusing to encode as noted [here](https://jansson.readthedocs.io/en/2.11/conformance.html#strings). In the output encoding library we detect this and encode as base64 -- I wonder if this should be done here as well?...</small>

<a href='https://github.com/flux-framework/flux-core/issues/5696' target='_blank'>View Comment</a>