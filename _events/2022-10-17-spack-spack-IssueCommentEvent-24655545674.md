---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/299842?"
user: tgamblin
date: 2022-10-17
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/33383
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/tgamblin' target='_blank'>tgamblin</a> commented on issue <a href='https://github.com/spack/spack/pull/33383' target='_blank'>spack/spack#33383</a>.

<small>I am not sure what we can do about this.  We pin `black` to 21.12b0 in our CI and in `spack style` because that's the last version of `black` that supports Python 2.7.  Unfortunately, this issue is present *in* that version of `black`, and will only be fixed in newer versions if it's fixed at all (and then only b/c it affects Python 3.5)....</small>

<a href='https://github.com/spack/spack/pull/33383' target='_blank'>View Comment</a>