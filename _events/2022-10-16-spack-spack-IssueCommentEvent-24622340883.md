---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/19558067?"
user: alecbcs
date: 2022-10-16
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/27769
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/alecbcs' target='_blank'>alecbcs</a> commented on issue <a href='https://github.com/spack/spack/pull/27769' target='_blank'>spack/spack#27769</a>.

<small>Just tested this on an M1 MacBook and I'm actually seeing `platform.machine()` report the system architecture as `arm64` instead of `aarch64` and so it's falling through to `go-bootstrap` and failing. @trws is there a technical difference between `aarch64` and `arm64` or should we be reporting the two as equivalent in Spack? (And standardizing on one naming convention vs another?)...</small>

<a href='https://github.com/spack/spack/pull/27769' target='_blank'>View Comment</a>