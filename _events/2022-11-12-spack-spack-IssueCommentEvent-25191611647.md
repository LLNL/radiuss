---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12021217?"
user: adamjstewart
date: 2022-11-12
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/33857
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/adamjstewart' target='_blank'>adamjstewart</a> commented on issue <a href='https://github.com/spack/spack/issues/33857' target='_blank'>spack/spack#33857</a>.

<small>Ah, this is relatively easy to explain/solve. The first time you run Spack, it searches your OS for compilers and puts them in a `compilers.yaml` file (generally in `~/.spack/linux/compilers.yaml`, although this file can live in other locations too). If you don't have a Fortran compiler available when this happens, Spack won't update `compilers.yaml` for you, even if you install it later. You can confirm that only C/C++ compilers are listed using:...</small>

<a href='https://github.com/spack/spack/issues/33857' target='_blank'>View Comment</a>