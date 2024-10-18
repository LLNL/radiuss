---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-10-17
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/47044
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/spack/spack/issues/47044' target='_blank'>spack/spack#47044</a>.

<small>Hi @adrienbernede, `hipsparse` is a required dependency under the specified conditions: `@4.4.0:+rocm`. The assumption in the `mfem` package is that all ROCm/HIP packages (`hip`, `hipsparse`, `hipblas`, `rocblas`, `rocrand`, etc) are all either external or they are all installed by Spack -- anything else does not really make sense to me. Therefore, the logic for `hipsparse` checks if `hip` is external and handles the two cases based on that....</small>

<a href='https://github.com/spack/spack/issues/47044' target='_blank'>View Comment</a>