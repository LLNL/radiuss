---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/38933153?"
user: eugeneswalker
date: 2023-01-27
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/34222
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/eugeneswalker' target='_blank'>eugeneswalker</a> commented on issue <a href='https://github.com/spack/spack/pull/34222' target='_blank'>spack/spack#34222</a>.

<small>For instance, I was able to reproduce the `libpressio +cuda` build error. And, picking up where the build failed, I can manually tell it to link specifically to the stub that is included already in the CI build environment. The problem is, `libpressio` is trying to link against `libcuda.so.1` but the stub comes as `libcuda.so`. If you just simply create a symlink `libcuda.so.1 -> libcuda.so (the stub)` , libpressio will build in the current CI environment. The question is, is this really necessary? Is there some way to get `libpressio` to try to link against `libcuda.so` ? If it is necessary to have the symlink, how can we create the symlink? Modify the package.py for `libpressio` so it can detect when this is needed and just create the symlink itself? I don't know what the best approach is, but it seems rational that we should use the stub library for it's intended purpose, which is exactly what this use case is....</small>

<a href='https://github.com/spack/spack/pull/34222' target='_blank'>View Comment</a>