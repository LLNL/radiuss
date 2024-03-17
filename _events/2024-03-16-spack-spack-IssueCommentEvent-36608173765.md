---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/765740?"
user: giordano
date: 2024-03-16
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/41151
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/giordano' target='_blank'>giordano</a> commented on issue <a href='https://github.com/spack/spack/pull/41151' target='_blank'>spack/spack#41151</a>.

<small>This is complicated 😢  It depends on #41738, and even with that PR merged, I'm not entirely sure Julia's SparseArrays package will play nicely with SuiteSparse v7.4.0, because the version of that stdlib bundled with Julia v1.10 was written with compatibility for an earlier version of SuiteSparse (I think 7.2.0 or 7.3.0 or something like that).  This should be fixed in Julia v1.11.0 (it supports newer versions of SuiteSparse, with better build system), but v1.10 is in awkward position, unless someone goes through the pain of packaging SuiteSparse v7.2-7.3 here in Spack....</small>

<a href='https://github.com/spack/spack/pull/41151' target='_blank'>View Comment</a>