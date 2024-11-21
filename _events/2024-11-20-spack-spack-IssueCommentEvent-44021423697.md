---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/112395?"
user: mabraham
date: 2024-11-20
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/47679
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/mabraham' target='_blank'>mabraham</a> commented on issue <a href='https://github.com/spack/spack/pull/47679' target='_blank'>spack/spack#47679</a>.

<small>I think `intel-oneapi-runtime` and `gcc-runtime` do a good job of modelling how a package like `gromacs` should be able to resolve the dependency on `libstdc++`. I think the GROMACS `package.py` should be able to declare requirements on libstdc++ (which should be versioned as GROMACS requirements evolve) via `gcc-runtime`, and only if no currently available `gcc-runtime` can do the job is one obtained via requiring a new installation of `gcc` package. Either way, GROMACS can be configured to use the matching `libstdc++.so`, *and* the user can have control via `^gcc-runtime@x.y` if they need that. I'll see if I can make that work. Any feedback?...</small>

<a href='https://github.com/spack/spack/pull/47679' target='_blank'>View Comment</a>