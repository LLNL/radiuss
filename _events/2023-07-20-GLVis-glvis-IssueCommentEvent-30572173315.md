---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11507994?"
user: rw-anderson
date: 2023-07-20
repo_name: GLVis/glvis
html_url: https://github.com/GLVis/glvis/issues/261
repo_url: https://github.com/GLVis/glvis
---

<a href='https://github.com/rw-anderson' target='_blank'>rw-anderson</a> commented on issue <a href='https://github.com/GLVis/glvis/issues/261' target='_blank'>GLVis/glvis#261</a>.

<small>I think the upshot of this is that the numbering that you specify in the ncmesh file defines parent-child relationships for the ncmesh. What glvis is showing you is not the contents of the "ncmesh" data structure (which contains the entire refinement tree from root nodes to leaves), but the "mesh" data structure information, which is a collapsed view of the mesh that contains only the leaf elements. Because of this, the vertex numberings can be different....</small>

<a href='https://github.com/GLVis/glvis/issues/261' target='_blank'>View Comment</a>