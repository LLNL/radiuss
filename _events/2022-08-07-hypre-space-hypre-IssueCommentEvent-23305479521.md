---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/44545837?"
user: njsyw1997
date: 2022-08-07
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/709
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/njsyw1997' target='_blank'>njsyw1997</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/709' target='_blank'>hypre-space/hypre#709</a>.

<small>@victorapm Thanks a lot for your reference output. I think I find my bug. The problem is the thread number. If I do not explicityly set `OMP_NUM_THREADS`, the therad number will be the max of the available on the machine, which is 128 on my server.  And according to my test, the threads cannot be more than 64.  I am using the Hypre release v2.25.0. Here are the outputs in case they are helpful for you....</small>

<a href='https://github.com/hypre-space/hypre/issues/709' target='_blank'>View Comment</a>