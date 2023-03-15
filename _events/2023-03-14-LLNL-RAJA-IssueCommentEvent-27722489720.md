---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/190171?"
user: YohannDudouit
date: 2023-03-14
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1458
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/YohannDudouit' target='_blank'>YohannDudouit</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1458' target='_blank'>LLNL/RAJA#1458</a>.

<small>Thank you @artv3 for opening this. Let me give a bit of context. Cuda and Hip both provide natively a 3D indexing for the threads `Dim3`, I think it would be great if Raja was providing a generalization of this, i.e. `ThreadBlock< Dim >`. Ideally, I would be able to access these thread indices through global functions/variables ( similarly to `ThreadIdx.?` ), not through an object similar to `LaunchContext` which pollutes interfaces too much....</small>

<a href='https://github.com/LLNL/RAJA/issues/1458' target='_blank'>View Comment</a>