---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/42977?"
user: msimberg
date: 2025-04-02
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/49202
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/msimberg' target='_blank'>msimberg</a> commented on issue <a href='https://github.com/spack/spack/issues/49202' target='_blank'>spack/spack#49202</a>.

<small>Adding another potential use case, which is currently broken with the new compilers-as-nodes changes: `intel-oneapi-mkl` and other oneapi packages want to query the openmp libraries to pass on to consumers, but if `intel-oneapi-mkl` is external there are no dependencies, and thus no compiler, to query for libraries. It's possible that oneapi needs to change and not the design for the new API, but adding this here for the record anyway....</small>

<a href='https://github.com/spack/spack/issues/49202' target='_blank'>View Comment</a>