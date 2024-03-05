---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2024-03-04
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4065
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4065' target='_blank'>mfem/mfem#4065</a>.

<small>Updating here after debugging this odd `misaligned address` error. Walking through with `cuda-gdb`, the error is actually being encountered inside of cuSPARSE's spMV, and in particular here is the true error message thrown by cuSPARSE:...</small>

<a href='https://github.com/mfem/mfem/pull/4065' target='_blank'>View Comment</a>