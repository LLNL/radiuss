---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/31893844?"
user: luckyqsz
date: 2025-06-09
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4879
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/luckyqsz' target='_blank'>luckyqsz</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4879' target='_blank'>mfem/mfem#4879</a>.

<small>I found the solution of this problem. Besides using '-d cuda', we still need to set the environment of SUPERLU_ACC_OFFLOAD by 'export SUPERLU_ACC_OFFLOAD=1'. In this way, the superlu test can use GPUs....</small>

<a href='https://github.com/mfem/mfem/issues/4879' target='_blank'>View Comment</a>