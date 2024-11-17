---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-11-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4580
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4580' target='_blank'>mfem/mfem#4580</a>.

<small>When you are building your test code and you have `MFEM_USE_SIMD=NO` (I suspect this is the case that you call "1 double"), do you have the compiler flags `-O3`, `-march=native`, and `--param max-completely-peel-times=3`? If you do, the compiler will still try to auto-vectorize the code and can do pretty well. That's probably why this case is not as slow as you might expect....</small>

<a href='https://github.com/mfem/mfem/issues/4580' target='_blank'>View Comment</a>