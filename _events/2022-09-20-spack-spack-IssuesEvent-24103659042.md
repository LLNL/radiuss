---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/4656391?"
user: wdconinc
date: 2022-09-20
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/18086
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/wdconinc' target='_blank'>wdconinc</a> closed issue <a href='https://github.com/spack/spack/issues/18086' target='_blank'>spack/spack#18086</a>.

<p>Valid concretization requiring older version is not found in dependency resolution</p><small>Due a pinned version on the libzqm dependency of cppzmq, but an open version libzqm dependency in py-pyzmq, a bundle package that depends on both cppzmq and py-pyzmq results in an unsatisfiable version constraint even though a satisfiable version can be hinted at (and, arguably, should have been found). This may point to a class of unsatisfiable version constraints elsewhere that can be resolved....</small><a href='https://github.com/spack/spack/issues/18086' target='_blank'>View Comment</a>