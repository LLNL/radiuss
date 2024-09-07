---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/334483?"
user: davidbeckingsale
date: 2024-09-06
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/pull/908
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/davidbeckingsale' target='_blank'>davidbeckingsale</a> commented on issue <a href='https://github.com/LLNL/Umpire/pull/908' target='_blank'>LLNL/Umpire#908</a>.

<small>> Thinking about this a bit more, this isn't quite right either. There's a missing counter, which is the high water mark of "current bytes". In QuickPool, `m_current_bytes` is what is used for `getCurrentSize` which correctly accounts for overallocation. `m_current_size` from `AllocationStrategy` does not take into account overallocation. Should this rather introduce a new counter in `QuickPool` which does the high water mark for `m_current_bytes` instead of `m_current_size`?...</small>

<a href='https://github.com/LLNL/Umpire/pull/908' target='_blank'>View Comment</a>