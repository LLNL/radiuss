---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5429263?"
user: liruipeng
date: 2024-06-04
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1096
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/liruipeng' target='_blank'>liruipeng</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1096' target='_blank'>hypre-space/hypre#1096</a>.

<small>Hi @v-dobrev Thank you for reporting this issue. This is a code design philosophy we have had from the beginning of the GPU work. When hypre is not configured with GPU, we treat HOST to be the "DEVICE", so there is no #ifdef of setting the default memory space to HYPRE_MEMORY_DEVICE, regardless of GPU or not. And the assert (among many others in the same form I guess) basically just say A and G lives in the same "device" space. Apparently, MFEM treat this differently. Does it work in the GPU case? ...</small>

<a href='https://github.com/hypre-space/hypre/issues/1096' target='_blank'>View Comment</a>