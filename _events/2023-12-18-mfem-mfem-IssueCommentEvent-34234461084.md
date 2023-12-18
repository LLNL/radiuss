---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-12-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3922
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3922' target='_blank'>mfem/mfem#3922</a>.

<small>Another option could be to use an int value to define the real type, e.g. `MFEM_REAL_TYPEID` with predefined macros like `MEM_DOUBLE_TYPEID` and `MFEM_FLOAT_TYPEID`/`MFEM_SINGLE_TYPEID`. Then in the code we can do preprocessor comparisons like `#if MFEM_REAL_TYPEID == MFEM_DOUBLE_TYPEID`. Users will define `MFEM_REAL_TYPEID=MFEM_DOUBLE_TYPEID`. Instead of `_TYPEID` we can use the shorter `_ID` or something like that. As before, for user convenience, we can add preprocessing in the build systems so they can just set the type as a string, `double`, `float`, etc....</small>

<a href='https://github.com/mfem/mfem/pull/3922' target='_blank'>View Comment</a>