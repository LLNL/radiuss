---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-11-14
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/6440
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/6440' target='_blank'>flux-framework/flux-core#6440</a>.

<small>I see you decided to re-restrict the line length to 80.  While we do generally try to hit 80 we don't actually follow it everywhere but clang-format will enforce it. Running a little script to get line lengths of every C source file in src/, filtering out libev and some of the other external things we vendor.  There are 466 lines that are between 80 and 88 lines long, and 540 more that are above 88 characters long.  A lot of the longer ones (especially over 100 chars) are in the tests, so that mostly doesn't count, but here are the files impacted by at least one line between 80 and 88 characters:...</small>

<a href='https://github.com/flux-framework/flux-core/pull/6440' target='_blank'>View Comment</a>