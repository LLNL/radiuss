---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7504421?"
user: bangerth
date: 2024-06-04
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/500
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/bangerth' target='_blank'>bangerth</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/500' target='_blank'>LLNL/sundials#500</a>.

<small>Yea, good question. I don't think we ever really understood what to pass there. We store, apply, access, and solve with solvers ourselves. All this happens in what users provide in the `solve_with_jacobian()` callback we attach to `ops->solve`. On large problems, this is *usually* an iterative solver, but at the end of the day the details should not matter to KINSOL since it has no part in the process of solving these linear systems -- the only reason why we set anything at all here is because we want to be informed about the target precision we need to solve with....</small>

<a href='https://github.com/LLNL/sundials/issues/500' target='_blank'>View Comment</a>