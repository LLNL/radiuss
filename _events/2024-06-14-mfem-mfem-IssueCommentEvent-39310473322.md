---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-06-14
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4350
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4350' target='_blank'>mfem/mfem#4350</a>.

<small>@lindsayad , it is an alternative approach, not only implementation, to solution of advection-diffusion equation (or similar) mentioned in #91 . Conceptually, the work of G. N. Wells weakly enforces continuity of all quantities without a difference, while Nguyen & Cockburn only apply this on the total flux. Such formulation then can benefit from the local conservation property and nicely work even without hybridization like RTDG or LDG (which we keep full compatibility with here, so a single line turns on the hybridization or not :wink: ). Moreover, there might be physical cases when discontinuity of the potential is desirable like Riemann problems. Anyway, there might be good reasons for the G. N. Wells approach as well, but it is closer to the technique of static condensation (with some extra stabilization), which is offered in MFEM on the algebraic level for `BilinearForm`, but not mixed systems unfortunately. This would be an interesting question if these techniques really coincide for discretely compatible trace spaces and the stabilization is not needed or not... 🤔 ...</small>

<a href='https://github.com/mfem/mfem/pull/4350' target='_blank'>View Comment</a>