---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2023-12-22
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1219
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> open issue <a href='https://github.com/LLNL/conduit/issues/1219' target='_blank'>LLNL/conduit#1219</a>.

<p>Is passing NULL to Node::set_external valid behavior?</p><small>I am debugging some code in which a host code exposes some of its internal data as a Blueprint tree of data. The code makes a topology and some fields. Some of the fields were apparently allocated later. At the time the Blueprint fields are created, some of the arrays are NULL and the host makes nodes anyway and calls set_external(), passing NULL pointers! Back in my library, I get the host code's node (which contains some NULLs) and I passed this node to conduit::relay::io::save() to save a conduit_json representation of the host code's mesh and fields. This causes relay to die because some of the external nodes are NULL....</small><a href='https://github.com/LLNL/conduit/issues/1219' target='_blank'>View Comment</a>