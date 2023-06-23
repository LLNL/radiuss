---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7978778?"
user: snehring
date: 2023-06-23
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/38517
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/snehring' target='_blank'>snehring</a> commented on issue <a href='https://github.com/spack/spack/issues/38517' target='_blank'>spack/spack#38517</a>.

<small>There's a behavior change here for sure, but the actual issue seems to be some of the parts of apptainer require -O0, and blindly overriding that for everything causes the errors. I've made changes to the cc wrapper that ignore spack provided optimization flags if the package has specified -O0, but that seems extremely specific  and maybe not the best way to solve this problem....</small>

<a href='https://github.com/spack/spack/issues/38517' target='_blank'>View Comment</a>