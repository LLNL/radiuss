---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-07-21
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6128
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6128' target='_blank'>flux-framework/flux-core#6128</a>.

<small>Right, I should have mentioned I saw that was fixed, sorry. The current behavior seems to be that "flux run -n 8 abort" say runs eight rank 0 processes. Everything works in the one test that sets PSM3_HAL though? And I can't offhand remember what that does. Clearly something going funny with PMI so I was vaguely hoping it was related, maybe needing a fix on the mpich side or a different workaround from us. ...</small>

<a href='https://github.com/flux-framework/flux-core/pull/6128' target='_blank'>View Comment</a>