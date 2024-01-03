---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2024-01-03
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3922
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3922' target='_blank'>mfem/mfem#3922</a>.

<small>Before these commits that removed usage of typedefs `KDTree1D`, `KDTree2D`, and `KDTree3D`, there were compiler errors in the github CI, although there were no problems for me on mac and LC. This issue seems to be caused by PR 4016, which introduced the templated `KDTreeBase` class. I don't see the problem, and it seems only some compilers fail. Does anyone have a suggestion, or should we simply remove these typedefs that only occurred a few times?...</small>

<a href='https://github.com/mfem/mfem/pull/3922' target='_blank'>View Comment</a>