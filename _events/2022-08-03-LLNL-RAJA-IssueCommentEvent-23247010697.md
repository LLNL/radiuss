---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2646848?"
user: MrBurmark
date: 2022-08-03
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1295
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/MrBurmark' target='_blank'>MrBurmark</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1295' target='_blank'>LLNL/RAJA#1295</a>.

<small>Looking more closely at the Segment implementations, RangeSegment is basically the same as Span, it holds two iterators. RangeStrideSegment is similar, it also holds size so division is only done at construction. Should we consider condensing the implementation of the RangeSegments and Span into one type?...</small>

<a href='https://github.com/LLNL/RAJA/pull/1295' target='_blank'>View Comment</a>