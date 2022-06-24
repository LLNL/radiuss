---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/166624?"
user: omsai
date: 2022-06-24
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/31151
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/omsai' target='_blank'>omsai</a> commented on issue <a href='https://github.com/spack/spack/issues/31151' target='_blank'>spack/spack#31151</a>.

<small>If I install the same version of blas++ with exactly the versions of dependencies you use I cannot reproduce the error.  The only difference in our dependency graph is I pull in ca-certificates-mozilla for openssl, but I don't expect that would be related.  I'm using the same operating system version and compiler, so the only other variable is the architecture: your newer skylake vs my many years older nehalem machine.  openblas has architecture-specific behavior so I wonder whether there's some issue with `libopenblas.so` on skylake....</small>

<a href='https://github.com/spack/spack/issues/31151' target='_blank'>View Comment</a>