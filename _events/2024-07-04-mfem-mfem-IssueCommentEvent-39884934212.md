---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-07-04
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4381
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4381' target='_blank'>mfem/mfem#4381</a>.

<small>I'll just add one remark: if linking with `libmfem.a` fails due to missing dependencies, it may be easiest to switch to a shared mfem build in spack (i.e. use spec `mfem+shared`) then `find_library(...)` should find `libmfem.so` which should already have all required dependencies linked in....</small>

<a href='https://github.com/mfem/mfem/issues/4381' target='_blank'>View Comment</a>