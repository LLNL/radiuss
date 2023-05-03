---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13971568?"
user: becker33
date: 2023-05-02
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/36762
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/becker33' target='_blank'>becker33</a> commented on issue <a href='https://github.com/spack/spack/pull/36762' target='_blank'>spack/spack#36762</a>.

<small>@haampie I believe the reason is performance, but I don't have a strong sense of how much of a performance difference it is. It's probably most notable for folks with large DBs on slow filesystems, since the biggest win is probably combining all the updates to set `explicit: true` for the root packages that were already installed into one transaction....</small>

<a href='https://github.com/spack/spack/pull/36762' target='_blank'>View Comment</a>