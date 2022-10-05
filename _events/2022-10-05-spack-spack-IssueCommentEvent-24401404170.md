---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4886803?"
user: cgmb
date: 2022-10-05
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/31450
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/cgmb' target='_blank'>cgmb</a> commented on issue <a href='https://github.com/spack/spack/pull/31450' target='_blank'>spack/spack#31450</a>.

<small>The failures are because the build is passing `-DAMDGPU_TARGETS:STRING=gfx1030;gfx701` but `gfx701` is not a supported architecture. Where is that value coming from? The target list only specifies `amdgpu_target=gfx1030`....</small>

<a href='https://github.com/spack/spack/pull/31450' target='_blank'>View Comment</a>