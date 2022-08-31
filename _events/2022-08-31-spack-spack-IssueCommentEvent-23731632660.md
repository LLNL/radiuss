---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/106587?"
user: dylex
date: 2022-08-31
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/27372
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/dylex' target='_blank'>dylex</a> commented on issue <a href='https://github.com/spack/spack/pull/27372' target='_blank'>spack/spack#27372</a>.

<small>Yes, I agree `overwrite` explicitly says it does both things, but I don't see a way to do it separately, so doing it manually should be fine.  I would add it to the existing function and use the same logic just with `".a"` instead of `soext`, so it only creates the `libcurses.a -> libncurses.a` symlink if libcurses.a doesn't exist and libncurses.a does: https://github.com/spack/spack/blob/develop/var/spack/repos/builtin/packages/ncurses/package.py#L181...</small>

<a href='https://github.com/spack/spack/pull/27372' target='_blank'>View Comment</a>