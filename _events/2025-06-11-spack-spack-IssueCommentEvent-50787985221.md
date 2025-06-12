---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12021217?"
user: adamjstewart
date: 2025-06-11
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/50862
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/adamjstewart' target='_blank'>adamjstewart</a> commented on issue <a href='https://github.com/spack/spack/pull/50862' target='_blank'>spack/spack#50862</a>.

<small>Personally, I would move all of `llnl` into `spack`. For `external`, we should try to directly use pip-installed dependencies. If there is anything in `external` that isn't on PyPI, I would also move it into `spack`. Of course, we would need to discuss this since it doesn't preserve the current directory structure. But that would solve all of our problems....</small>

<a href='https://github.com/spack/spack/pull/50862' target='_blank'>View Comment</a>