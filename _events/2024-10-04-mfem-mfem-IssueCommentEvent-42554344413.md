---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1929159?"
user: sshiraiwa
date: 2024-10-04
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4530
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sshiraiwa' target='_blank'>sshiraiwa</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4530' target='_blank'>mfem/mfem#4530</a>.

<small>I already tried to skip it by %ignore directive in SWIG, but it does not work, probably because this line does not make sense at all for SWIG. While we don't need to expose it in Python binding, SWIG need to know the MFEM_REGISTER_KERNELS macro, which is defined above in the same file, in order to interpret bilininteg.hpp and quadinterpolator.hpp. ...</small>

<a href='https://github.com/mfem/mfem/issues/4530' target='_blank'>View Comment</a>