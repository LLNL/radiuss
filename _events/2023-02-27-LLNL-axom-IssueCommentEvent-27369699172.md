---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2023-02-27
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/issues/994
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> commented on issue <a href='https://github.com/LLNL/axom/issues/994' target='_blank'>LLNL/axom#994</a>.

<small>I noticed that for the last span of the above spline that the front of the span would not refine, even as more line segments were added. When I looked into it more, I found that the curvature in the span was not monotonic, which is something the initial algorithm assumed. I made some changes to sample the curvature derivative within the span and look for sign changes. If sign changes are located, the code solves for the u value where the derivative changes signs (a min or max). These values are used to partition the span into smaller monotonic regions and we calculate the min/max curvature more accurately. Then segments are apportioned to the intervals based on the interval lengths. The image below shows the curvature within the last problematic span....</small>

<a href='https://github.com/LLNL/axom/issues/994' target='_blank'>View Comment</a>