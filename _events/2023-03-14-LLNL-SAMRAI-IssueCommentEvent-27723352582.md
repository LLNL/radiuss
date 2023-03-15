---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17625866?"
user: nselliott
date: 2023-03-14
repo_name: LLNL/SAMRAI
html_url: https://github.com/LLNL/SAMRAI/issues/222
repo_url: https://github.com/LLNL/SAMRAI
---

<a href='https://github.com/nselliott' target='_blank'>nselliott</a> commented on issue <a href='https://github.com/LLNL/SAMRAI/issues/222' target='_blank'>LLNL/SAMRAI#222</a>.

<small>One thing you could try is building SAMRAI develop or 4.2.0 with the older BLT, commit `2c192774b587c245ec2d7022b2e862395ffa8a21` which is BLT v0.3.0.  We were years behind on BLT releases, but the older BLT should still work for x86_64/gnu builds, so you could `cd` into the `blt` submodule subdirectory in SAMRAI and checkout that commit and try to build.  That could verify that this is due to a change in BLT, and you could proceed through subsequent BLT releases to narrow down when the change occurred....</small>

<a href='https://github.com/LLNL/SAMRAI/issues/222' target='_blank'>View Comment</a>