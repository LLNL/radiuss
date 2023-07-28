---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/34423936?"
user: cfriedland5
date: 2023-07-27
repo_name: LLNL/merlin
html_url: https://github.com/LLNL/merlin/issues/435
repo_url: https://github.com/LLNL/merlin
---

<a href='https://github.com/cfriedland5' target='_blank'>cfriedland5</a> open issue <a href='https://github.com/LLNL/merlin/issues/435' target='_blank'>LLNL/merlin#435</a>.

<p>subprocess in check_for_scheduler can also raise PermissionError</p><small>In [get_batch_type](https://github.com/LLNL/merlin/blob/12ff3d782d30579b1387eb314f33924d33d1877f/merlin/study/batch.py#L99) when checking for pbs [check_for_scheduler](https://github.com/LLNL/merlin/blob/12ff3d782d30579b1387eb314f33924d33d1877f/merlin/study/batch.py#L68) raised an uncaught exception because the subprocess raised a PermissionError rather than a FileNotFoundError....</small><a href='https://github.com/LLNL/merlin/issues/435' target='_blank'>View Comment</a>