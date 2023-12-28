---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2023-12-28
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1223
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> open issue <a href='https://github.com/LLNL/conduit/issues/1223' target='_blank'>LLNL/conduit#1223</a>.

<p>conduit::blueprint::mesh::topology::unstructured::verify passes on polygonal mesh with no sizes.</p><small>I was given a boundary mesh that is unstructured with "polygonal" zones but it did not have sizes. That seems **BAD** since without sizes, we would have to guess the number of points per zone. I passed this mesh to the _unstructured::verify_ function and it passes whereas it should probably fail for polygonal meshes when sizes are missing....</small><a href='https://github.com/LLNL/conduit/issues/1223' target='_blank'>View Comment</a>