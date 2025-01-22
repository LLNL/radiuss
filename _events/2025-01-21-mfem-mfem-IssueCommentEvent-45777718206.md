---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/14336752?"
user: psocratis
date: 2025-01-21
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4651
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/psocratis' target='_blank'>psocratis</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4651' target='_blank'>mfem/mfem#4651</a>.

<small>@adam-sim-dev, I am a bit confused. What does this PR fix? For sure it does not resolve the empty rank 0 issue, does it? @v-dobrev I do think there is an issue with CPardiso internals, basically I can't accept a negative value for `iparm[41]`. So if we  use something like `iparm[40] = 1, `iparm[41] = 0` (instead of 0, -1 respectively) it seems that the issue is indeed fixed. ...</small>

<a href='https://github.com/mfem/mfem/pull/4651' target='_blank'>View Comment</a>