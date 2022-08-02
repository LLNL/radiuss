---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11876153?"
user: drreynolds
date: 2022-08-01
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/182
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/drreynolds' target='_blank'>drreynolds</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/182' target='_blank'>LLNL/sundials#182</a>.

<small>@ciropom: you will need to emulate the code from `cvLsDenseDQJac` ([here](https://github.com/LLNL/sundials/blob/main/src/cvode/cvode_ls.c#L1034)), but ensuring that each of the operations use device-resident vector data, and that these operations fill device-resident data within the MKL matrix. ...</small>

<a href='https://github.com/LLNL/sundials/issues/182' target='_blank'>View Comment</a>