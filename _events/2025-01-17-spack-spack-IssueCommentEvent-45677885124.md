---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/33492707?"
user: G-Ragghianti
date: 2025-01-17
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/48631
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/G-Ragghianti' target='_blank'>G-Ragghianti</a> commented on issue <a href='https://github.com/spack/spack/pull/48631' target='_blank'>spack/spack#48631</a>.

<small>I found a CI check was failing due to a missing definition of rocm-core.  It was not included in the spack package version()s because they did not tag the release 5.7.3 of rocm-core, however they did release binaries of it.  This is what we are currently using at our site.  I added a version("5.7.3") in rocm-core without a sha256.  I'm not sure if this is the best way to deal with this situation.  Ideas?...</small>

<a href='https://github.com/spack/spack/pull/48631' target='_blank'>View Comment</a>