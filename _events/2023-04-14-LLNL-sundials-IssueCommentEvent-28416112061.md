---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/8794797?"
user: mottelet
date: 2023-04-14
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/273
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/mottelet' target='_blank'>mottelet</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/273' target='_blank'>LLNL/sundials#273</a>.

<small>@gardner48 : I am exploring the possibilities of wrapping Sundials solvers into a differential delay equations solver. Like I said above, when the delays can become smaller than the actual solver predicted step, the approach used in Julia is to do fixed point iterations. In the case of CVode, the initial Nordsieck vectors set would be those of the previous step (hence used for extrapolation), and for further iterations the Nordsieck vectors of previous iteration are used. Hence this approach would need to allow CVodeGetDky to use a kind of checkpoint mechanism (i.e. have currently updated  Nordsieck vectors and also the previous iteration/freezed Nordsieck vectors)....</small>

<a href='https://github.com/LLNL/sundials/issues/273' target='_blank'>View Comment</a>