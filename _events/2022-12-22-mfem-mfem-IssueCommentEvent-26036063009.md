---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5429263?"
user: liruipeng
date: 2022-12-22
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3370
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/liruipeng' target='_blank'>liruipeng</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3370' target='_blank'>mfem/mfem#3370</a>.

<small>@v-dobrev hypre uses the device id that is set before `HYPRE_Init`, see https://github.com/hypre-space/hypre/blob/45b6cdb1a00cf0ae39904345954db081c148343b/src/utilities/general.c#L307. So you should try `hipSetDevice(1)` somewhere before calling `HYPRE_Init`....</small>

<a href='https://github.com/mfem/mfem/issues/3370' target='_blank'>View Comment</a>