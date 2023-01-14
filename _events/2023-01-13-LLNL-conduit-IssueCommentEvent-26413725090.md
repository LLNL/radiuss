---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/528611?"
user: FreddieWitherden
date: 2023-01-13
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1065
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/FreddieWitherden' target='_blank'>FreddieWitherden</a> commented on issue <a href='https://github.com/LLNL/conduit/issues/1065' target='_blank'>LLNL/conduit#1065</a>.

<small>Another option is just to bite the bullet and define a v2 C API wherein *all* functions return a status code (with existing return values being converted to parameter arguments).  These functions can all be suffixed with `_v2`.  Then, in the header one can have an #ifdef which does #define conduit_node_append conduit_node_append_v2 such that new consumers of the API do not need to worry about the suffix....</small>

<a href='https://github.com/LLNL/conduit/issues/1065' target='_blank'>View Comment</a>