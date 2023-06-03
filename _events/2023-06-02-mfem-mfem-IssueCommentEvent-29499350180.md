---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2023-06-02
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3526
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3526' target='_blank'>mfem/mfem#3526</a>.

<small>> Previously, methods like `PADiffusionSetup2D<2>` were defined once and used multiple times. The modifications proposed here make the same method `inline` and so its use in different translation units will result in multiple copies. For small low level functions this makes sense, however, for methods like `PADiffusionSetup2D<2>` this just slows down compilation and inflates the size of the generated code unnecessarily....</small>

<a href='https://github.com/mfem/mfem/pull/3526' target='_blank'>View Comment</a>