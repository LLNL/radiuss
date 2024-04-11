---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-04-11
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/42314
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> closed issue <a href='https://github.com/spack/spack/issues/42314' target='_blank'>spack/spack#42314</a>.

<p>LLVM: Is cxx11 still a dependency?</p><small>Currently for package llvm, `flags.append(self.compiler.cxx11_flag)` still lies in `packages.py`, although llvm had been using c++17 partly; that makes in compilation of some files, cxx11 flag (from spack) and cxx17 flag (from cmake) appear in one single command....</small><a href='https://github.com/spack/spack/issues/42314' target='_blank'>View Comment</a>