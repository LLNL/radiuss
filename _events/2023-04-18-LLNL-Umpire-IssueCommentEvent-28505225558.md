---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/28022856?"
user: CameronRutherford
date: 2023-04-18
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/issues/800
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/CameronRutherford' target='_blank'>CameronRutherford</a> commented on issue <a href='https://github.com/LLNL/Umpire/issues/800' target='_blank'>LLNL/Umpire#800</a>.

<small>I was able to repro the same issues as @jaelynlitz using latest spack develop and the same system. I verified that the BLT exclude configuration was being passed to umpire, and nothing on the system path should be linked in. I also verified with `cpp` while in the spack environment that `/usr/lib/;/lib` were not on the include search path....</small>

<a href='https://github.com/LLNL/Umpire/issues/800' target='_blank'>View Comment</a>