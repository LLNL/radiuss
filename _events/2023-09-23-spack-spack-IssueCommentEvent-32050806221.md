---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/98330?"
user: rgommers
date: 2023-09-23
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/40057
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/rgommers' target='_blank'>rgommers</a> commented on issue <a href='https://github.com/spack/spack/pull/40057' target='_blank'>spack/spack#40057</a>.

<small>Any BLAS/LAPACK is supported, the problem is detecting it usually. It looks from the log that the installed shared libraries are ` ['libsci_cray_mpi.so', 'libsci_cray.so']`, but that's not helpful. `setup-args=-Dblas=sci_cray_mpi` comes up empty, so there's no `.pc` file with that name apparently....</small>

<a href='https://github.com/spack/spack/pull/40057' target='_blank'>View Comment</a>