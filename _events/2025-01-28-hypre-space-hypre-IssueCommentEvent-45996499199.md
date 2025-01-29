---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1138252?"
user: iaae
date: 2025-01-28
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1210
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/iaae' target='_blank'>iaae</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1210' target='_blank'>hypre-space/hypre#1210</a>.

<small>Thanks for all suggestions and I can now get a stable Hypre pre/solve for the next stage of benchmark/eval.  It turned out the Cmake configured on VS2019 the Hypre project "using Intel MPI" but after reviewing the lib/dll/exe dependency, it is still linked with msmpi.dll.  After fixing all inconsistency settings using MS_MPI and MS_OpenMP, things are running consistently.  The initial result shows that Hypre is about 50% speed of our in-house code but is showing good potential as it has not been fully tuned yet....</small>

<a href='https://github.com/hypre-space/hypre/issues/1210' target='_blank'>View Comment</a>