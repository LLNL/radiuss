---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/48997041?"
user: agcapps
date: 2023-11-27
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/pull/1224
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/agcapps' target='_blank'>agcapps</a> commented on issue <a href='https://github.com/LLNL/axom/pull/1224' target='_blank'>LLNL/axom#1224</a>.

<small>After a spirited discussion on November 27 2023, the consensus was that we (Axom developers) don't like the static global variable.  Within `load()` and allies, we will temporarily save the error handler, set it to default, and do the Conduit operations within a try/catch block.  Afterward, restore the error handler....</small>

<a href='https://github.com/LLNL/axom/pull/1224' target='_blank'>View Comment</a>