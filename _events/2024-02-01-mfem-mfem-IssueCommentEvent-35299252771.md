---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-02-01
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4101
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4101' target='_blank'>mfem/mfem#4101</a>.

<small>Yes, these warnings are `nvcc` specific -- other compilers do not issue them. Looking at our internal nightly CUDA tests, I now see the warnings, however they do not trigger failures, so we do not see them usually. Maybe we can change the test behavior to trigger failures on warnings....</small>

<a href='https://github.com/mfem/mfem/pull/4101' target='_blank'>View Comment</a>