---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2022-11-04
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/33684
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/spack/spack/issues/33684' target='_blank'>spack/spack#33684</a>.

<small>In the MFEM `package.py`, we do not modify the C++ compiler -- neither the Spack wrapper, `env["CXX"]`, nor the actual C++ compiler called by the Spack wrapper, `env["SPACK_CXX"]`. The switch to `nvcc` happens inside the MFEM build system. This way the compilation chain for host code is: `nvcc` -> `mpicxx` -> Spack C++ wrapper -> actual compiler....</small>

<a href='https://github.com/spack/spack/issues/33684' target='_blank'>View Comment</a>