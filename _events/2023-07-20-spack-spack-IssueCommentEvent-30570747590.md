---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5642668?"
user: balay
date: 2023-07-20
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/38537
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/balay' target='_blank'>balay</a> commented on issue <a href='https://github.com/spack/spack/pull/38537' target='_blank'>spack/spack#38537</a>.

<small>> Yes. The type of hypre__global_error has changed, but line 2043 shouldn't exist outside of hypre (it's an internal global variable in hypre). I looked at the PETSc repo, and this line doesn't seem to be in the current version of this file. Is this an old version of PETSc?...</small>

<a href='https://github.com/spack/spack/pull/38537' target='_blank'>View Comment</a>