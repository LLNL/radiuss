---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11307?"
user: dev-zero
date: 2023-04-02
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/36600
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/dev-zero' target='_blank'>dev-zero</a> commented on issue <a href='https://github.com/spack/spack/issues/36600' target='_blank'>spack/spack#36600</a>.

<small>Interesting, I wonder what changed 🤔. This is either an `--as-needed` and library order bug when linking (since libxsmm is linked statically, the blas/lapack libs should come after it in the linker line). Respectively the `libxsmmf*.pc` file is missing the blas/lapack library....</small>

<a href='https://github.com/spack/spack/issues/36600' target='_blank'>View Comment</a>