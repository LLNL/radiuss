---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11876153?"
user: drreynolds
date: 2022-09-18
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/195
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/drreynolds' target='_blank'>drreynolds</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/195' target='_blank'>LLNL/sundials#195</a>.

<small>I'm not sure that I understand your request, @mottelet.  Although `ARKStepSetTables` does not immediately check that the inputs `Bi` and `Be` are lower-triangular and strictly-lower-triangular, respectively, those compatibility checks are indeed performed by ARKStep soon thereafter.  Since this is the one routine where users can manually specify the tables, the documentation for this function should indeed mention that the tables will be checked for compatibility....</small>

<a href='https://github.com/LLNL/sundials/issues/195' target='_blank'>View Comment</a>