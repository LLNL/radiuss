---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13821049?"
user: CRobeck
date: 2022-12-10
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1404
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/CRobeck' target='_blank'>CRobeck</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1404' target='_blank'>LLNL/RAJA#1404</a>.

<small>> Thanks for discovering this difference, I would have never suspected that `alignof(std::max_align_t)` would be different in host code and device code. I'm surprised that such an inconsistency between the host and device was allowed to come into being. It seems problematic in a fundamental way if we want generic code that can work together on both the host and device. @trws What do you think of this?...</small>

<a href='https://github.com/LLNL/RAJA/pull/1404' target='_blank'>View Comment</a>