---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/630436?"
user: Chrismarsh
date: 2025-05-12
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/50351
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/Chrismarsh' target='_blank'>Chrismarsh</a> commented on issue <a href='https://github.com/spack/spack/pull/50351' target='_blank'>spack/spack#50351</a>.

<small>I ended up removing that line of `package.py` to force it to configure, and `arrow buildsystem=cmake ^thrift build_system=autotools` worked for me.  So that's not it. I am using `thrift@0.21.0` -- can you try that instead of `@0.20`? I can't find much of a change log between them. I run into this from time to time, https://github.com/spack/spack/issues/45983, where I have to deactivate then re activate the env for it to pick up paths correctly. ...</small>

<a href='https://github.com/spack/spack/pull/50351' target='_blank'>View Comment</a>