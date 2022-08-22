---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17242663?"
user: blue42u
date: 2022-08-22
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/32193
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/blue42u' target='_blank'>blue42u</a> commented on issue <a href='https://github.com/spack/spack/issues/32193' target='_blank'>spack/spack#32193</a>.

<small>After some more experimentation, I was able to build something of a reproducer for issue (2). Apparently the spec is not re-hashed when loading JSON, so if the hash changes it is possible to install identical packages with different hashes, one of which gets "lost":...</small>

<a href='https://github.com/spack/spack/issues/32193' target='_blank'>View Comment</a>