---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2023-12-27
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4035
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4035' target='_blank'>mfem/mfem#4035</a>.

<small>There are certain MFEM configuration options that will lead to duplicate libraries in the link command when you build any of the examples, for example a parallel build with `MFEM_USE_SUITESPARSE = YES` will include `-lmetis` twice (since `SUITESPARSE_LIB` includes the string `$(METIS_LIB)`)....</small>

<a href='https://github.com/mfem/mfem/pull/4035' target='_blank'>View Comment</a>