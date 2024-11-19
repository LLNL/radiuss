---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/52063692?"
user: Wayne901
date: 2024-11-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4580
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/Wayne901' target='_blank'>Wayne901</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4580' target='_blank'>mfem/mfem#4580</a>.

<small>Well I test the result for different compiler flags on CPU architecture, and on different CPUs. Faster runtime on cpu supporting avx512 than avx2 is observed. The only question is the benefit of increasing vectorization from 4 doubles to 8 doubles is not very obvious. I think the DoFs (6.3 million) are not small for 1 process. I really hope to explore the best power of mfem's matrix-free method on our server....</small>

<a href='https://github.com/mfem/mfem/issues/4580' target='_blank'>View Comment</a>