---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-06-08
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3689
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3689' target='_blank'>mfem/mfem#3689</a>.

<small>Forgive the drive by, but @termi-official If I am understanding you correctly: No, quadrature rules on simplices are not in general constructed from combination of 1D rules on lines. See https://arxiv.org/pdf/1409.1865.pdf for a very interesting paper about how to construct simplex rules whilst respecting all the relevant symmetries. It's an interesting exercise trying to figure out the relevant symmetries for the first 2 or 3 gauss rules on a triangle (or tet) by hand, it pretty quickly starts to get out of hand but is enlightening. With a change of measure, it's even possible to derive the simplest rules on tri/tet using 1D rules in barycentric coordinates, this breaks down very quickly though....</small>

<a href='https://github.com/mfem/mfem/issues/3689' target='_blank'>View Comment</a>