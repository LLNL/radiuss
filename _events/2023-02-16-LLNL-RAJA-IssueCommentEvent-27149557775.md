---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2646848?"
user: MrBurmark
date: 2023-02-16
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1368
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/MrBurmark' target='_blank'>MrBurmark</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1368' target='_blank'>LLNL/RAJA#1368</a>.

<small>Hmm, it looks like its trying to call the host version of makeDispatcher but it sohuld be calling the device version. The fix may be as simple as adding Platform::omp_target in dispatcher_use_host_invoke....</small>

<a href='https://github.com/LLNL/RAJA/issues/1368' target='_blank'>View Comment</a>