---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2023-10-30
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/commit/84872303010b8e8e6b0763a8c649ba95369e3f85
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> pushed to <a href='https://github.com/LLNL/maestrowf' target='_blank'>LLNL/maestrowf</a>

<small>Fix flux job cancellation (#428)

Update v0.49 and v0.26 flux script adapters to adapt cancellation machinery to work with recent update to submit machinery that converts from flux JobID to native types.

Update general cancellation behaviors:
* Check for in progress steps before declaring cancelled successfully to delay until actual final states can be serialized
* Update cancel logic to mirror failure logic: mark all steps downstream of a cancelled step to also be cancelled</small>

<a href='https://github.com/LLNL/maestrowf/commit/84872303010b8e8e6b0763a8c649ba95369e3f85' target='_blank'>View Commit</a>