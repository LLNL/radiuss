---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4656391?"
user: wdconinc
date: 2024-05-05
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/44006
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/wdconinc' target='_blank'>wdconinc</a> commented on issue <a href='https://github.com/spack/spack/pull/44006' target='_blank'>spack/spack#44006</a>.

<small>I guess the failure scenario I'm imagining is someone running `spack containerize --list-os`, seeing `fedora:38` (since parsed from images.json), and using that to start their container build from. `FROM spack/fedore38 as builder` will still work, but it won't be an updated image anymore....</small>

<a href='https://github.com/spack/spack/pull/44006' target='_blank'>View Comment</a>