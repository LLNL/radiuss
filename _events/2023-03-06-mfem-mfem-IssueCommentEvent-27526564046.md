---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2023-03-06
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3088
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3088' target='_blank'>mfem/mfem#3088</a>.

<small>@IdoAkkerman Good point, that the failure for a non-NURBS mesh was not informative. I added an `MFEM_VERIFY` with an error message in `BilinearForm::Assemble`, since that function applies the integrators to a mesh. The integrators themselves do not know what mesh will be used, so we cannot check when defining the integrator....</small>

<a href='https://github.com/mfem/mfem/pull/3088' target='_blank'>View Comment</a>