---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/194764?"
user: haampie
date: 2024-12-10
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/47848
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/haampie' target='_blank'>haampie</a> commented on issue <a href='https://github.com/spack/spack/pull/47848' target='_blank'>spack/spack#47848</a>.

<small>You have to replace `depends_on("cub")` the package with `depends_on("cub-api")` the virtual. You can depend on a package without using its virtual, that's why both cuda and cub are allowed in one dag....</small>

<a href='https://github.com/spack/spack/pull/47848' target='_blank'>View Comment</a>