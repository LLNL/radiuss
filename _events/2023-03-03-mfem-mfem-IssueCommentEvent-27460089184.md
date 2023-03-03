---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-03-03
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3479
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3479' target='_blank'>mfem/mfem#3479</a>.

<small>Basically, the quadrature points, `ip`, on the reference face element are mapped to the volume reference element: `ip` is mapped to `eip1` and `eip2` where 1 and 2 denote the two adjacent volume elements, respectively. After that the basis functions are evaluated at these points for face integration. The velocity is computed on the face by evaluating the coefficient `u` on element 1 at the quadrature point `eip1`, as mentioned above....</small>

<a href='https://github.com/mfem/mfem/issues/3479' target='_blank'>View Comment</a>