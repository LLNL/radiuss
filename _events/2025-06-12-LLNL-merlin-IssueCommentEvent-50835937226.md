---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/49216024?"
user: bgunnar5
date: 2025-06-12
repo_name: LLNL/merlin
html_url: https://github.com/LLNL/merlin/pull/512
repo_url: https://github.com/LLNL/merlin
---

<a href='https://github.com/bgunnar5' target='_blank'>bgunnar5</a> commented on issue <a href='https://github.com/LLNL/merlin/pull/512' target='_blank'>LLNL/merlin#512</a>.

<small>@lucpeterson it looks like those three main issues that I tagged in my last comment are all related to the containerized server functionality rather than LaunchIT. I've been working on a fix for these on the #513 branch (not yet pushed) but one of the issues (https://github.com/LLNL/merlin/security/code-scanning/25) breaks Redis if we try to fix it. I tried replacing the sha256 hash with an argon2 hash like it suggested, but it turns out Redis requires an sha256 hash for its passwords. With that being said I am still going to try to add Fernet encryption to our backend logic for the containerized server, which should resolve the other two complaints....</small>

<a href='https://github.com/LLNL/merlin/pull/512' target='_blank'>View Comment</a>