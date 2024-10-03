---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-10-02
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1305
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1305' target='_blank'>flux-framework/flux-sched#1305</a>.

<small>apologies if this is obvious but just in case not, that system is configured with  `match-format = "rv1_nosched"` and has an R containing JGF.  Recently it was discovered that the R was not riight and it was regenerated and the scheduler reloaded with the system idle.  Well, almost, we discovered a stuck job in housekeeping from before this morning which was causing `flux resource list` to report "duplicate allocation in housekeeping".   The stuck nodes were rebooted before 9AM and that stopped.  However the above messages appear to still be popping up....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1305' target='_blank'>View Comment</a>