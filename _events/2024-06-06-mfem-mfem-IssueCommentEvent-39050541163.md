---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/52063692?"
user: Wayne901
date: 2024-06-06
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4340
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/Wayne901' target='_blank'>Wayne901</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4340' target='_blank'>mfem/mfem#4340</a>.

<small>I know where was I wrong now. The `VectorFEMassIntegrator` has similar scheme as `DiffusionIntgerator`, and the inverse Jacobian is multiplied in `PADiffusionSetup2/3D` function. I guess boundary PA assembly should follow `PADiffusionSetup2D<3>` rather than `PADiffusionSetup2D<2>` for nedelec element?...</small>

<a href='https://github.com/mfem/mfem/issues/4340' target='_blank'>View Comment</a>