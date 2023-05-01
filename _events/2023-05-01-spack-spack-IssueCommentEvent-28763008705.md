---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2828630?"
user: rbberger
date: 2023-05-01
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/37284
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/rbberger' target='_blank'>rbberger</a> commented on issue <a href='https://github.com/spack/spack/pull/37284' target='_blank'>spack/spack#37284</a>.

<small>@Andrey1994 Spack already sets `icx` and such as compilers when using `%oneapi`. OpenMP is enabled properly via CMake. And `-qopenmp-simd` is enabled by default with `-O2` and higher. So, again, what specifically does the preset change that supposetly makes a difference? (we created the LAMMPS presets for local development, but I fail to see the value in the Spack case)....</small>

<a href='https://github.com/spack/spack/pull/37284' target='_blank'>View Comment</a>