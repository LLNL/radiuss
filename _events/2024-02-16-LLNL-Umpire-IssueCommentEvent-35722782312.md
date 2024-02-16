---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12800412?"
user: rhornung67
date: 2024-02-16
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/pull/870
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/rhornung67' target='_blank'>rhornung67</a> commented on issue <a href='https://github.com/LLNL/Umpire/pull/870' target='_blank'>LLNL/Umpire#870</a>.

<small>@kab163 we've had similar issues with RAJA. The cause is that the containers contain a bunch of Spack stuff that is not needed and azure reduced the amount of disk space allowed for free accounts. Chris was working on building a new container repo to address this but I don't know what the status of that is. For RAJA, we turned off nvcc and rocm checks in azure since we are covering those cases in LC GItLab CI. ...</small>

<a href='https://github.com/LLNL/Umpire/pull/870' target='_blank'>View Comment</a>