---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-08-03
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1295
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1295' target='_blank'>LLNL/RAJA#1295</a>.

<small>In the end, we probably want them all to be "ranges", and "views" in the c++20 sense, which means a combination of an iterator and a sentinel, and in the case of a view it also means that move or copy construction is O(1).  In principle the numeric ranges are the same as a span over an iterator, rather than a pointer.  They could be the same thing as long as we keep the check logic in a creation function.  ...</small>

<a href='https://github.com/LLNL/RAJA/pull/1295' target='_blank'>View Comment</a>