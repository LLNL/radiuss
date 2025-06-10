---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2025-06-09
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/20423
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/20423' target='_blank'>visit-dav/visit#20423</a>.

<small>@biagas what you are describing is *exactly* the issue we were seeing with the recent `ElementBlock*1` expression on Exodus files. The *singletons* are created in the expression system for constants. So, in this example, the `1` in the expression gets handled that way.  But, then its singleton-ness got lost sometime later in expression evaluation and it contained garbage data. So, exactly what you were describing....</small>

<a href='https://github.com/visit-dav/visit/issues/20423' target='_blank'>View Comment</a>