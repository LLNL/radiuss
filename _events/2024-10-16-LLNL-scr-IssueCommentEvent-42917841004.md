---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2024-10-16
repo_name: LLNL/scr
html_url: https://github.com/LLNL/scr/pull/596
repo_url: https://github.com/LLNL/scr
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/LLNL/scr/pull/596' target='_blank'>LLNL/scr#596</a>.

<small>I realized when testing with the flux launcher that the flux launcher's default behavior is to send stdout and stderr to Flux's KVS, so nothing would be printed by `scr_run` even after this PR. However, it's not lost, so I'm not sure how much of an issue it is as opposed to just a behavioral difference between Flux and e.g. Slurm. However it might be nice if the Flux launcher printed out job ids......</small>

<a href='https://github.com/LLNL/scr/pull/596' target='_blank'>View Comment</a>