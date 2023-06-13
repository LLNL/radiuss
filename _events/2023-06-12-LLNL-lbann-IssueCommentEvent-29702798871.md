---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/30674819?"
user: benson31
date: 2023-06-12
repo_name: LLNL/lbann
html_url: https://github.com/LLNL/lbann/issues/2276
repo_url: https://github.com/LLNL/lbann
---

<a href='https://github.com/benson31' target='_blank'>benson31</a> commented on issue <a href='https://github.com/LLNL/lbann/issues/2276' target='_blank'>LLNL/lbann#2276</a>.

<small>yeah, NVIDIA/nccl#835 is the root cause of that. Short of convincing LC to install modern compilers on the system, the best fix is to just force NCCL to build at a lower version. For the LBANN build script, add `^nccl@2.16.2-1` to the end of the spec you pass to the build script....</small>

<a href='https://github.com/LLNL/lbann/issues/2276' target='_blank'>View Comment</a>