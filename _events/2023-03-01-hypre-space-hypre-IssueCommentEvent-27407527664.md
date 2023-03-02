---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13603403?"
user: lprc
date: 2023-03-01
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/412
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/lprc' target='_blank'>lprc</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/412' target='_blank'>hypre-space/hypre#412</a>.

<small>OK I figured out with `HYPRE_SetExecutionPolicy(HYPRE_EXEC_HOST);` the code will run on host, nice! Maybe the documentation should reflect this. There is no describing comment for this function either. I still don't know why the example does not run on the GPU, even if I insert `HYPRE_SetExecutionPolicy(HYPRE_EXEC_DEVICE);` right after `HYPRE_Init()` but at least it works for my own code....</small>

<a href='https://github.com/hypre-space/hypre/issues/412' target='_blank'>View Comment</a>