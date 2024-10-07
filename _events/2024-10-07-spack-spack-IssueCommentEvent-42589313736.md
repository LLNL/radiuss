---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/8276147?"
user: georgiastuart
date: 2024-10-07
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/46823
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/georgiastuart' target='_blank'>georgiastuart</a> commented on issue <a href='https://github.com/spack/spack/pull/46823' target='_blank'>spack/spack#46823</a>.

<small>@tgamblin I pushed up my proposed solution. I wanted to preserve the ability to use the `os.path` functions since they're cross-platform and have better logic than I wanted to replicate, so I tried to solve this by changing `os.environ` as needed with the `FrozenEnvironment` context manager I added. It should "freeze" the env whenever an object is instanciated from the class, and I added an `INITIAL_ENVIRONMENT` var that should initialize before any environment modifications are done. Seems to work fine and I don't think it should have any unintended consequences. `canonicalize_path` should use `INITIAL_ENVIRONMENT` by default, but that can be set to `None` or a different `FrozenEnvironment` object if needed....</small>

<a href='https://github.com/spack/spack/pull/46823' target='_blank'>View Comment</a>