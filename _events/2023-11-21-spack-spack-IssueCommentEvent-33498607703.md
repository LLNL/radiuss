---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2023-11-21
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/41121
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/spack/spack/issues/41121' target='_blank'>spack/spack#41121</a>.

<small>What platforms did you observe build errors for? I am able to build `libxsmm` without the changes introduced by #40494 on non-x86_64 platforms just fine (on AWS Graviton as well as Mac M1). Is there perhaps a more refined conflict suggestion you could use to replace `requires("target=x86_64:")` in the `libxsmm` recipe? I guess my point is that this is overly restrictive as `libxsmm` supports non-x86_64 systems as far as I can tell....</small>

<a href='https://github.com/spack/spack/issues/41121' target='_blank'>View Comment</a>