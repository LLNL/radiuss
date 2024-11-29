---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/50467563?"
user: victorapm
date: 2024-11-28
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/1181
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/victorapm' target='_blank'>victorapm</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/1181' target='_blank'>hypre-space/hypre#1181</a>.

<small>Hi Adam, I can't reproduce this on Ubuntu, gcc-11 and nvcc 12.6. Could you try a fresh build (remove cmbuild and call cmake again). Another idea is to disable LTO and enable verbose mode with `-DCMAKE_INTERPROCEDURAL_OPTIMIZATION=OFF -DCMAKE_VERBOSE_MAKEFILE=ON`...</small>

<a href='https://github.com/hypre-space/hypre/pull/1181' target='_blank'>View Comment</a>