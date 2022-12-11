---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4656391?"
user: wdconinc
date: 2022-12-10
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/34448
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/wdconinc' target='_blank'>wdconinc</a> commented on issue <a href='https://github.com/spack/spack/pull/34448' target='_blank'>spack/spack#34448</a>.

<small>Just to be clear, this failed to build for me (gcc-12, ubuntu22.10) without `libxaw`, then I checked the `CMakeLists.txt` and added both of them. In this case, it appears that `libxt` is transitively included via the `motif` dependency. Still, it makes sense to add the explicit dependency....</small>

<a href='https://github.com/spack/spack/pull/34448' target='_blank'>View Comment</a>