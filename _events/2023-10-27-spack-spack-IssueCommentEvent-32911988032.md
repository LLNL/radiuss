---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12021217?"
user: adamjstewart
date: 2023-10-27
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/40734
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/adamjstewart' target='_blank'>adamjstewart</a> commented on issue <a href='https://github.com/spack/spack/pull/40734' target='_blank'>spack/spack#40734</a>.

<small>The same kind of thing appears in scipy as well. I believe these are the minimum versions of numpy needed for support for those versions of Python. @rgommers can you explain why scipy adds these to `pyproject.toml`? I'm guessing it's something to do with building the most compatible possible binary for each Python version (numpy may add features but is less likely to remove them). I'm pretty sure we can skip them and let the concretizer ensure that compatible versions are chosen....</small>

<a href='https://github.com/spack/spack/pull/40734' target='_blank'>View Comment</a>