---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-04-13
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/50033
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/spack/spack/pull/50033' target='_blank'>spack/spack#50033</a>.

<small>What issue are you encountering? libCEED does not call BLAS directly, but libXSMM has a transitive dependency on BLAS so if you enable libXSMM, you should also specify `BLAS_LIB` (because spack strives to be explicit). If that's consistent with what you've observed, can you update this PR to only be used when libXSMM is enabled?...</small>

<a href='https://github.com/spack/spack/pull/50033' target='_blank'>View Comment</a>