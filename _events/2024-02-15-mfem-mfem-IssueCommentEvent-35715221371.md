---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6109571?"
user: mlstowell
date: 2024-02-15
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4118
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/mlstowell' target='_blank'>mlstowell</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4118' target='_blank'>mfem/mfem#4118</a>.

<small>I should also mention that the reason to compute the gradient as a Nedelec field is that the Nedelec basis functions contain the gradients of the H1 basis functions so no global solve is necessary. The Nedelec gradient can be computed using a `LinearInterpolator` rather than a `BilinearForm` (see https://mfem.org/lininterp/) and no global solve will be necessary....</small>

<a href='https://github.com/mfem/mfem/issues/4118' target='_blank'>View Comment</a>