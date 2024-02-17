---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-02-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4114
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4114' target='_blank'>mfem/mfem#4114</a>.

<small>I am not sure if it is it, but it maybe you are mistaking the dimensions here 😮 😵 . There are two types of elements: scalar and vector. Scalar elements (like L2), as the name suggests, represent scalar values. When you want to represent a vector by them, you need to use the vector dimension of the FE space, which stacks them on top of each other. In contrast, vector finite elements (like ND) represent certain components of vector fields of the dimension given by the mesh. Unless you want to represent something multi-valued like complex amplitude or something like that, you should use vector dimension equal to 1 for them 😉 ...</small>

<a href='https://github.com/mfem/mfem/issues/4114' target='_blank'>View Comment</a>