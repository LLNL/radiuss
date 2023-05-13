---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17625866?"
user: nselliott
date: 2023-05-12
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1115
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/nselliott' target='_blank'>nselliott</a> commented on issue <a href='https://github.com/LLNL/conduit/issues/1115' target='_blank'>LLNL/conduit#1115</a>.

<small>`conduit::blueprint::mpi::mesh::generate_domain_to_rank_map()` creates a mapping between domain IDs and rank numbers that is intended to be stored in the root file for this purpose, when the IDs may be scattered unpredictably among the ranks.  It sounds like `save_mesh` is something that should make use of this.  However I'm not sure the support in the VisIt plugin to read that map is available yet....</small>

<a href='https://github.com/LLNL/conduit/issues/1115' target='_blank'>View Comment</a>