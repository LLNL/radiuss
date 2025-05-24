---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1659704?"
user: scheibelp
date: 2025-05-23
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/50616
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/scheibelp' target='_blank'>scheibelp</a> commented on issue <a href='https://github.com/spack/spack/pull/50616' target='_blank'>spack/spack#50616</a>.

<small>I see in [e46a9f2](https://github.com/spack/spack/pull/50616/commits/e46a9f24fe6bcc6e100a8eaaa154a888f232e17c) that the spec this was trying to attach python to was `llvm`: `llvm` extends python (in this case) but is not a `PythonPackage`, so it's implementation of `_update_external_dependencies ` (inherited from `PackageBase`) is a noop (i.e. no attempt to call `detection.by_path`)....</small>

<a href='https://github.com/spack/spack/pull/50616' target='_blank'>View Comment</a>