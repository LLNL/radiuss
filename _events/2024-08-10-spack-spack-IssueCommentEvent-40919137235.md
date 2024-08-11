---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/598250?"
user: mdorier
date: 2024-08-10
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/41174
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/mdorier' target='_blank'>mdorier</a> commented on issue <a href='https://github.com/spack/spack/issues/41174' target='_blank'>spack/spack#41174</a>.

<small>@haampie I don't know if this is related but in an environment I just did `spack develop -p mycode mycode@main` in an environment, from the directory containing the `mycode` folder, then `spack add mycode@main`, and `spack install`, but spack was trying to find the `mycode` source directory in the environment's path instead of the relive path I provided. I fixed it by doing `spack develop -p $(realpath mycode) mycode@main` instead, to provide an absolute path, but I think it should be expected that the path passed to `spack develop`, if relative, be relative to where the command is run, not related to where the environment will be installed....</small>

<a href='https://github.com/spack/spack/issues/41174' target='_blank'>View Comment</a>