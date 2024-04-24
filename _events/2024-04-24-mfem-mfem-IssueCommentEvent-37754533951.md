---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-04-24
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4262
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4262' target='_blank'>mfem/mfem#4262</a>.

<small>Yeah, that Ubuntu is really weird :face_with_spiral_eyes: , it looks like `pow(float, float)` gives `double` there. That should not be according to C++98 already. However, my theory is that it does some optimization maybe as the second parameter is just an integer casted to float, so it then uses `pow(float, int)`, where [was historically some ambiguity about the return type](https://cplusplus.github.io/LWG/issue550). ...</small>

<a href='https://github.com/mfem/mfem/pull/4262' target='_blank'>View Comment</a>