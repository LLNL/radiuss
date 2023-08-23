---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/1194526?"
user: cyrush
date: 2023-08-22
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/907
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/cyrush' target='_blank'>cyrush</a> closed issue <a href='https://github.com/LLNL/conduit/issues/907' target='_blank'>LLNL/conduit#907</a>.

<p>Representing structured data with equal-sized element and vertex arrays</p><small>One particular data format we want to represent in Blueprint stores the same count of vertices and elements along a dimension.  (Mesh Blueprint needs to represent n+1 vertices with n elements.)  This data format is a block-structured mesh with two ghost zones.  Here is an example of a mesh with one element field and one vertex field.  The "real" data is 3 columns by 2 rows and the format stores two ghost zones at each end of each dimension, so the element data, vertex data, and vertex positions are all size 7x6....</small><a href='https://github.com/LLNL/conduit/issues/907' target='_blank'>View Comment</a>