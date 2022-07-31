---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/98330?"
user: rgommers
date: 2022-07-30
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/31810
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/rgommers' target='_blank'>rgommers</a> commented on issue <a href='https://github.com/spack/spack/pull/31810' target='_blank'>spack/spack#31810</a>.

<small>This indeed doesn't work with `pip`/`build`, only with `meson`. It looks like that needs fixing in `meson-python`. If you want to get `1.9.0` packages out without delay, perhaps you should still build them with `numpy.distutils` - all that's needed I think is a one-line patch to remove `build-backend = 'mesonpy'` from `pyproject.toml`....</small>

<a href='https://github.com/spack/spack/pull/31810' target='_blank'>View Comment</a>