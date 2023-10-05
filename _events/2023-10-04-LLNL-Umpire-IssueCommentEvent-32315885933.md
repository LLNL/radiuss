---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12800412?"
user: rhornung67
date: 2023-10-04
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/pull/850
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/rhornung67' target='_blank'>rhornung67</a> commented on issue <a href='https://github.com/LLNL/Umpire/pull/850' target='_blank'>LLNL/Umpire#850</a>.

<small>It looks like you are running into disk space limits on azure. We ran into this in RAJA recently. After trying several things, I could not resolve the issue, which seems to be due to the rse-ops images containing a bunch of Spack remnants that we don't need and which cause testing to blow past the space limit. I removed our GPU builds, except for SYCL, on azure which we test on LC GitLab CI anyway. @white238 tried to resolve the issue with res-ops folks, but was unable to make progress with them....</small>

<a href='https://github.com/LLNL/Umpire/pull/850' target='_blank'>View Comment</a>