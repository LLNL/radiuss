---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4656391?"
user: wdconinc
date: 2025-01-26
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/48597
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/wdconinc' target='_blank'>wdconinc</a> commented on issue <a href='https://github.com/spack/spack/pull/48597' target='_blank'>spack/spack#48597</a>.

<small>Turns out the pkgconfig dependency is still needed even when using external wxwidgets, so apologies for that incorrect comment here. Without pkgconfig, the gdk include directories are not found. See #48565 where I made that chance to get the CI stack to build. Previously failed in e.g. https://gitlab.spack.io/spack/spack/-/jobs/14786523. Upside is that that #48565 will ensure the wxpython build is exercised in CI....</small>

<a href='https://github.com/spack/spack/pull/48597' target='_blank'>View Comment</a>