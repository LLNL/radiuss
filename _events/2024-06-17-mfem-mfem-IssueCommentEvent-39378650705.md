---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-06-17
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4350
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4350' target='_blank'>mfem/mfem#4350</a>.

<small>You are right, it must be pointed out that LDG and HDG formulations are no longer equivalent here. HDG has better stabilization compared LDG, which misses one part as Cockburn mentions. This can be clearly seen when you try the centered scheme for advection-dominated problems. LDG performs poorly showing some oscillations, while HDG gives nicely smooth solution 👍 ....</small>

<a href='https://github.com/mfem/mfem/pull/4350' target='_blank'>View Comment</a>