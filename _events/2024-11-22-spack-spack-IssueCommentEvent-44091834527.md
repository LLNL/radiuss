---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/29245235?"
user: vucoda
date: 2024-11-22
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/47712
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/vucoda' target='_blank'>vucoda</a> commented on issue <a href='https://github.com/spack/spack/pull/47712' target='_blank'>spack/spack#47712</a>.

<small>In spack 0.23.0 when I bootstrap from source on some systems where `/usr/bin/python` = python 2 and `/usr/bin/python3` is python 3, the `python-venv` `spack` package using find_first() may pick up /usr/bin/python as the executable, then calling `/usr/bin/python -m venv` will fail. the above commit makes sure to find python3.xx or python3 before python...</small>

<a href='https://github.com/spack/spack/pull/47712' target='_blank'>View Comment</a>