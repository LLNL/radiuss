---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/14336752?"
user: psocratis
date: 2023-06-26
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3751
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/psocratis' target='_blank'>psocratis</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3751' target='_blank'>mfem/mfem#3751</a>.

<small>@sungho91, thanks for sharing the code. I do see the failure on my side though not at step 10. You might want to compile mfem in debugging mode to ensure that an out of bounds leak is caught. When I do that I see the error below at line `1108`.  Also I believe at lines 1122 and 1123 it should be `==`.  ...</small>

<a href='https://github.com/mfem/mfem/issues/3751' target='_blank'>View Comment</a>