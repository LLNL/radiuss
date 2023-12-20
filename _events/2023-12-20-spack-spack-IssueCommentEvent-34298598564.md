---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1802137?"
user: agseaton
date: 2023-12-20
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/41766
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/agseaton' target='_blank'>agseaton</a> commented on issue <a href='https://github.com/spack/spack/issues/41766' target='_blank'>spack/spack#41766</a>.

<small>I think I figured out what is making this slow. I had added the develop binary mirror (https://binaries.spack.io/develop). Removing it gives me more reasonable timings (4 seconds now for `spack spec gcc`), though at the cost of having to compile many more packages from source....</small>

<a href='https://github.com/spack/spack/issues/41766' target='_blank'>View Comment</a>