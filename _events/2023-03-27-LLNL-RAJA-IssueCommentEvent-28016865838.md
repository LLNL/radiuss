---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/190171?"
user: YohannDudouit
date: 2023-03-27
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1465
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/YohannDudouit' target='_blank'>YohannDudouit</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1465' target='_blank'>LLNL/RAJA#1465</a>.

<small>It's not clear, I'm benchmarking from ~1K to ~80M dofs, but my intuition is that the 100K - 10M range is probably what users are going to use the most. The performance is much better at lower dofs with `RAJA::hip_reduce_atomic`! The discrepancy appears above 5M dofs. I actually think that with `RAJA::hip_reduce_atomic` the overall performance on the range of interest is better, the peak performance is a bit lower but that's okay as I don't see users using as much very high dofs counts....</small>

<a href='https://github.com/LLNL/RAJA/issues/1465' target='_blank'>View Comment</a>