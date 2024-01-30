---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-01-29
repo_name: GLVis/glvis
html_url: https://github.com/GLVis/glvis/issues/269
repo_url: https://github.com/GLVis/glvis
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/GLVis/glvis/issues/269' target='_blank'>GLVis/glvis#269</a>.

<small>It looks like you need to write a mesh and data (displacement file -> MFEM grid function file) converters. A good starting point about the MFEM mesh formats is here: https://mfem.org/mesh-formats. The vector grid function format is described as part of the description of the `nodes` section in https://mfem.org/mesh-format-v1.x/#geometry -- e.g. for linear hex elements, one can use the string `H1_3D_P1` for the `FiniteElementCollection`....</small>

<a href='https://github.com/GLVis/glvis/issues/269' target='_blank'>View Comment</a>