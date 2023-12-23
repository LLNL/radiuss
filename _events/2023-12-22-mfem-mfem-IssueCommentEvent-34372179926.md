---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-12-22
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4045
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4045' target='_blank'>mfem/mfem#4045</a>.

<small>The logic for SuiteSparse is in the file `FindSuiteSparse.cmake` in `config/cmake/modules`. It uses the function `mfem_find_package` defined in `MfemCmakeUtilities.cmake` in the same directory. The names of the component libraries are given in `FindSuiteSparse.cmake` without the prefix `lib` and without extension, e.g. simply `umfpack`. One way to force static libraries is to replace `umfpack` with `libumfpack.a`....</small>

<a href='https://github.com/mfem/mfem/issues/4045' target='_blank'>View Comment</a>