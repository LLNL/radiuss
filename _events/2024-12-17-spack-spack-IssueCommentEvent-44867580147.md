---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/765740?"
user: giordano
date: 2024-12-17
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/33237
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/giordano' target='_blank'>giordano</a> commented on issue <a href='https://github.com/spack/spack/issues/33237' target='_blank'>spack/spack#33237</a>.

<small>For the record, I ran into this in an environment with a few hundreds R packages.  While trying to install a package the `R_LIBS` env var (you can see it with `spack -e /path/to/env build-env /czoe47a7`, where `/czoe47a7` is the hash of the package in question) includes 428 directories and is about 150 kB (~ 𝄹 / 100 :stuck_out_tongue:), which larger than `MAX_ARG_STRLEN`, resulting in `git` failing to start:...</small>

<a href='https://github.com/spack/spack/issues/33237' target='_blank'>View Comment</a>