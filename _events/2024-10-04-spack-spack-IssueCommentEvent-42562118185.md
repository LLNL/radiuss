---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-10-04
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/46784
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/46784' target='_blank'>spack/spack#46784</a>.

<small>I don't think it is.  My guess would be that because we pass the makeflags down through the environment, so the jobserver can work, the `--keep-going` flag is getting propagated _through spack_ and causing the output to change.  This seems reasonable to me, any issues @haampie?...</small>

<a href='https://github.com/spack/spack/pull/46784' target='_blank'>View Comment</a>