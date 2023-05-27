---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-05-26
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3676
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3676' target='_blank'>mfem/mfem#3676</a>.

<small>That would be quite plausible, as I just recently discovered a situation where exactly that could occur: when a triangle with no dofs is incorrectly indexed into by searching the `var_face_dofs` structure, see [here](https://github.com/mfem/mfem/issues/3691#issuecomment-1563109316). I believe this can be fixed by tweaking the use of `std::lower_bound(begin, end, val)` to `std::upper_bound(begin, end, val) - 1`, as the `entity -> dof` relation there can look like `0,0,0,1,2,3,3,3,4`, for tri, tri, **quad**, **quad**, **quad**, tri, tri, **quad** if p = 2.  Upper bound will catch the first index beyond the interval matching the predicate, whereas lower_bound is the first within the interval. Running this locally the `np=2` adapts and the resulting solution and mesh looks as expected....</small>

<a href='https://github.com/mfem/mfem/pull/3676' target='_blank'>View Comment</a>