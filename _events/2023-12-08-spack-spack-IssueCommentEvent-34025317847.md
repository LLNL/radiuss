---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/82525672?"
user: AlexanderRichert-NOAA
date: 2023-12-08
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/41283
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/AlexanderRichert-NOAA' target='_blank'>AlexanderRichert-NOAA</a> commented on issue <a href='https://github.com/spack/spack/pull/41283' target='_blank'>spack/spack#41283</a>.

<small>@adamjstewart unfortunately that has the effect of making some of the dependencies also use gcc. With a root spec of `py-cryptography%intel` and adding `conflicts("%intel")` (or `requires("%gcc")`), I get:...</small>

<a href='https://github.com/spack/spack/pull/41283' target='_blank'>View Comment</a>