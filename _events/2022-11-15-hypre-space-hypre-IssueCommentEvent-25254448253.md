---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5429263?"
user: liruipeng
date: 2022-11-15
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/775
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/liruipeng' target='_blank'>liruipeng</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/775' target='_blank'>hypre-space/hypre#775</a>.

<small>@stgeke I don't see issues with "setup only once but run the solver at every time step". We have backward Euler time stepping test. You can setup AMG once and call solve at each time with a new vector (without destroying the matrix). I don't see problems with the globals. (You don't need to call `HYPRE_Init` multiple times where basically the globals are created)....</small>

<a href='https://github.com/hypre-space/hypre/issues/775' target='_blank'>View Comment</a>