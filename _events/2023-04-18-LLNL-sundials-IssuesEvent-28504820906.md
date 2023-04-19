---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/7504421?"
user: bangerth
date: 2023-04-18
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/275
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/bangerth' target='_blank'>bangerth</a> open issue <a href='https://github.com/LLNL/sundials/issues/275' target='_blank'>LLNL/sundials#275</a>.

<p>nvgetcommunicator returning pointer to MPI_Comm leads to complicated designs.</p><small>For the deal.II wrappers of the N_Vector interface, we've had several lengthy discussions about how to deal with the `ops.nvgetcommunicator` callback. The basic problem is that that interface requires one to write a function that returns a *pointer* to a communicator -- and that requires that that communicator has a memory location where it can be accessed....</small><a href='https://github.com/LLNL/sundials/issues/275' target='_blank'>View Comment</a>