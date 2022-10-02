---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16190001?"
user: jthies
date: 2022-10-01
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/32111
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/jthies' target='_blank'>jthies</a> commented on issue <a href='https://github.com/spack/spack/issues/32111' target='_blank'>spack/spack#32111</a>.

<small>An issue I encounter when building phist %oneapi within spack is that "oneapi-mpi" sets the MPI compiler wrappers to "mpiicc", etc., which means that they will use icc, icpc and ifort rather than icx, icpx and ifx. This then leads to linker errors. I don't think this is a phist issue: we use this code to set the compilers to MPI wrappers:...</small>

<a href='https://github.com/spack/spack/issues/32111' target='_blank'>View Comment</a>