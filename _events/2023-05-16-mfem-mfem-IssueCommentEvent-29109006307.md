---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-05-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3671
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3671' target='_blank'>mfem/mfem#3671</a>.

<small>Update: the fix above involving `nullptr` seems to resolve this issue but uncovers an infinite loop in [this while loop](https://github.com/mfem/mfem/blob/master/fem/pfespace.cpp#L2527), wherein `nfinalized` is never equal to or exceeding `ndofs`. Only one rank ends up in the loop, as the other two ranks are no longer sending anything. Thus there appears to be a mismatch in number of local true dofs across processors. ...</small>

<a href='https://github.com/mfem/mfem/issues/3671' target='_blank'>View Comment</a>