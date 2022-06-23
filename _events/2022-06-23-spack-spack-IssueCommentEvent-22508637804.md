---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-06-23
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/30544
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/30544' target='_blank'>spack/spack#30544</a>.

<small>That has always been the default, except that it used to be essentially `Version("''.0")` or some similar version less than zero.  The intent of this PR is to make it more clear when a version will actually be resolved and when not, and improve the performance of dealing with a mix of regular and commit versions, and change the default to treat an unknown version as higher than any known version on the theory it is most likely a develop version rather than a version from the dawn of time....</small>

<a href='https://github.com/spack/spack/pull/30544' target='_blank'>View Comment</a>