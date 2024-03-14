---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/481429?"
user: aumuell
date: 2024-03-13
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/43170
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/aumuell' target='_blank'>aumuell</a> commented on issue <a href='https://github.com/spack/spack/pull/43170' target='_blank'>spack/spack#43170</a>.

<small>I'm not certain if it's worth the effort to provide a proper fix for this old version of mgard: to me it seems that `refactor_qz` is part of the public API, so changing that is probably not an option. So probably the best that could be done is to warn and terminate, if a dimension component becomes negative, instead of silently failing. But is it that likely that a single dimension component becomes that large?...</small>

<a href='https://github.com/spack/spack/pull/43170' target='_blank'>View Comment</a>