---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2024-05-14
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/19513
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/19513' target='_blank'>visit-dav/visit#19513</a>.

<small>FYI...Silo does support "array" variables. But, when the HDF5 driver was implemented (it came *after* the PDB driver), it placed a compile-time upper limit on the number of component variables which defaults to 16. Thats sad :cry:. So, the way this would be handled in Silo is with multiple `DBPutXxxvar()` calls and then a `DBPutDefvars()` call that created an array exprssion for the array variable....</small>

<a href='https://github.com/visit-dav/visit/issues/19513' target='_blank'>View Comment</a>