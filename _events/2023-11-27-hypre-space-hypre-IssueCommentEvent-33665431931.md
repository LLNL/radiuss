---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5429263?"
user: liruipeng
date: 2023-11-27
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1015
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/liruipeng' target='_blank'>liruipeng</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1015' target='_blank'>hypre-space/hypre#1015</a>.

<small>Hi @thartland If you only call `HYPRE_ParVectorDestroy` to free the object of IJVecotr, it is expected to have memory leak from the other parts of IJVector. `HYPRE_IJVectorDestroy` free them as well. I don't see the reason why you can't call `HYPRE_IJVectorDestroy` on `IJ_grad`. Maybe I missed something. If you have to just call `HYPRE_ParVectorDestroy` only, the only way is to manipulate the IJ structure, after `HYPRE_IJVectorGetObject`, by setting ...</small>

<a href='https://github.com/hypre-space/hypre/issues/1015' target='_blank'>View Comment</a>