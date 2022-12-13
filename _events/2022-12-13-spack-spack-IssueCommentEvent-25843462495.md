---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12021217?"
user: adamjstewart
date: 2022-12-13
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/34431
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/adamjstewart' target='_blank'>adamjstewart</a> commented on issue <a href='https://github.com/spack/spack/pull/34431' target='_blank'>spack/spack#34431</a>.

<small>`--test=root` should be possible for the ML stack, although I wouldn't be surprised if some bugs pop out. `--test=all` would break with a lot of circular deps. At the very least, we should run `spack test` after `spack install`. For Python packages, the main thing to be concerned about is import tests, which are included in both....</small>

<a href='https://github.com/spack/spack/pull/34431' target='_blank'>View Comment</a>