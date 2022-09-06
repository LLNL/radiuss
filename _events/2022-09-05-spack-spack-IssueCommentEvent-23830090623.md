---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1237199?"
user: simonpintarelli
date: 2022-09-05
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/32443
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/simonpintarelli' target='_blank'>simonpintarelli</a> commented on issue <a href='https://github.com/spack/spack/pull/32443' target='_blank'>spack/spack#32443</a>.

<small>Sorry for the delay. It should be correct now. `-DUSE_CRAY_LIBSCI` is passed to cmake if `^cray-libsci` is in the spec, scalapack can be turned on/off independently (this is how it is implemented in SIRIUS). If `~scalapack ^cray-libsci` is specified, BLAS/LAPACK functionality is taken from libsci, but parallel blas/lapack functionality remains disabled....</small>

<a href='https://github.com/spack/spack/pull/32443' target='_blank'>View Comment</a>