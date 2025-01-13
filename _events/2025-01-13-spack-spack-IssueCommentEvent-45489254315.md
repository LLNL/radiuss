---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3205938?"
user: DingXuefeng
date: 2025-01-13
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/48446
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/DingXuefeng' target='_blank'>DingXuefeng</a> commented on issue <a href='https://github.com/spack/spack/issues/48446' target='_blank'>spack/spack#48446</a>.

<small>Hi, I fully understood this bug now. The root of the bug is that, `root` load `libcppyy_backend.so` with `ctypes.CDLL`, and `ctypes.CDLL` does not read the RPATH. ...</small>

<a href='https://github.com/spack/spack/issues/48446' target='_blank'>View Comment</a>