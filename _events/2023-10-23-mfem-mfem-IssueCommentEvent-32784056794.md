---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/90462987?"
user: M8kmyday
date: 2023-10-23
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3947
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/M8kmyday' target='_blank'>M8kmyday</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3947' target='_blank'>mfem/mfem#3947</a>.

<small>This discussion is consistent with something I am seeing.  After posting this issue, I just started changing options on the mesh constructor and load methods to see what happens.  I found that setting refine=0 fixed the dof ordering issue for me.  I've been running my regression suites to see if this is a general fix (still running).  The vast majority of cases pass (10s of thousands), but some see some slight changes (say 0.1%).  I do use adaptive mesh refinement for some cases, so I don't know what refine=0 vs. refine=1 means and what it is doing.  It is possible that the newer results are better than the older result such that failing the test with a small change is not meaningful....</small>

<a href='https://github.com/mfem/mfem/issues/3947' target='_blank'>View Comment</a>