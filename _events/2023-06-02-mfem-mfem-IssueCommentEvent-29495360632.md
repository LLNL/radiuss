---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2023-06-02
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3526
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3526' target='_blank'>mfem/mfem#3526</a>.

<small>Thanks for looking into this closely @v-dobrev — good catch. It is possible that the change you point out is actually fine (since `T_Q1D` is a template parameter — and I believe `static constexpr` outside the lambda also works to avoid the issue in #852), but I completely agree that these kinds of changes should be evaluated **outside** of the context of a code reorganization....</small>

<a href='https://github.com/mfem/mfem/pull/3526' target='_blank'>View Comment</a>