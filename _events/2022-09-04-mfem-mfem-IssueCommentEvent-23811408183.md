---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17843342?"
user: vladotomov
date: 2022-09-04
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3189
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/vladotomov' target='_blank'>vladotomov</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3189' target='_blank'>mfem/mfem#3189</a>.

<small>`Vector::Norml2()` is a serial function, try with `inline double InnerProduct(MPI_Comm comm, const Vector &x, const Vector &y)` from `vector.hpp`, or do the reductions yourself....</small>

<a href='https://github.com/mfem/mfem/issues/3189' target='_blank'>View Comment</a>