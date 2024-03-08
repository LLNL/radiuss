---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-03-08
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4179
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4179' target='_blank'>mfem/mfem#4179</a>.

<small>I think the basic answer is: `GridFunction::ProjectCoefficient(Coefficient &coeff)` is not meant to be used with multi-component (vdim > 1) `GridFunction`s. This also applied to `GridFunction`s that use vector finite elements (like Nedelec or Raviart-Thomas FEs) even when vdim = 1....</small>

<a href='https://github.com/mfem/mfem/issues/4179' target='_blank'>View Comment</a>