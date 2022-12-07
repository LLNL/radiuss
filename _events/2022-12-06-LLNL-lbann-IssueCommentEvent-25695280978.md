---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/30674819?"
user: benson31
date: 2022-12-06
repo_name: LLNL/lbann
html_url: https://github.com/LLNL/lbann/issues/2162
repo_url: https://github.com/LLNL/lbann
---

<a href='https://github.com/benson31' target='_blank'>benson31</a> commented on issue <a href='https://github.com/LLNL/lbann/issues/2162' target='_blank'>LLNL/lbann#2162</a>.

<small>I agree, but it's the general preference of most of our users to have `-O3` and `-g`. Our tools all add it at every compilation level so that we always get good stack traces (or as good as they can be, I guess). It _shouldn't_ make any difference whatsoever (except in the final binary size), so it's really a Clang+BSD issue that this is happening. I don't see it with Clang 14 or Clang 15 on any of our Linux systems....</small>

<a href='https://github.com/LLNL/lbann/issues/2162' target='_blank'>View Comment</a>