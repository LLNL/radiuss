---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2023-04-04
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/36516
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> commented on issue <a href='https://github.com/spack/spack/issues/36516' target='_blank'>spack/spack#36516</a>.

<small>Hi @vsoch, I can answer some of your questions (sorry, I won't be much help on the `SPACK_CC_RPATH_ARG` problem). The installed `Makefile` and `CMakeLists.txt` files are auto-generated from the options used to configure sundials and I suspect there's either a problem with how we're generating the files or the Spack [post install actions](https://github.com/spack/spack/blob/develop/var/spack/repos/builtin/packages/sundials/package.py#L543) (or both)....</small>

<a href='https://github.com/spack/spack/issues/36516' target='_blank'>View Comment</a>