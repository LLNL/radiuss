---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20098718?"
user: waynemitchell
date: 2022-06-22
repo_name: XBraid/xbraid
html_url: https://github.com/XBraid/xbraid/issues/82
repo_url: https://github.com/XBraid/xbraid
---

<a href='https://github.com/waynemitchell' target='_blank'>waynemitchell</a> commented on issue <a href='https://github.com/XBraid/xbraid/issues/82' target='_blank'>XBraid/xbraid#82</a>.

<small>@lankes-fzj, it sounds to me like you do not need to be reading/writing from the GPU at all during the `step` routine. When XBraid calls `step`, it is pretty agnostic to what is happening under the hood in that call (e.g. it doesn't care where the data lives). So you should be able to leave the data on the GPU and let XBraid call `step` as usual. I can't say for sure, since I'm not familiar with the code you are wrapping....</small>

<a href='https://github.com/XBraid/xbraid/issues/82' target='_blank'>View Comment</a>