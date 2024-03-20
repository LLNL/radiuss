---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-03-20
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1616
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1616' target='_blank'>LLNL/RAJA#1616</a>.

<small>One comment based on yours @publixsubfan, all previously existing raja atomics were relaxed.  It's the stronger ones, and really the scopes, that are most interesting because they can mean we can pass data without having to do all loads and stores with atomics.  Block scope atomics, with device scope fences only when necessary, also are likely to help us greatly on El Cap.  The atomics themselves wont be faster, but there will be substantially less expensive cache invalidation....</small>

<a href='https://github.com/LLNL/RAJA/pull/1616' target='_blank'>View Comment</a>