---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/194764?"
user: haampie
date: 2022-08-02
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/31793
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/haampie' target='_blank'>haampie</a> commented on issue <a href='https://github.com/spack/spack/issues/31793' target='_blank'>spack/spack#31793</a>.

<small>The issue here is a combination of things: mbedtls does not set a proper `install_name` (not an absolute path, nor `@rpath/libname.dylib`, but simply `libname.dylib`), and this causes libraries not to be found at runtime, which curl checks....</small>

<a href='https://github.com/spack/spack/issues/31793' target='_blank'>View Comment</a>