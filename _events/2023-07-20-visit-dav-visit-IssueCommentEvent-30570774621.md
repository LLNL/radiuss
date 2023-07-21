---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1102718?"
user: brugger1
date: 2023-07-20
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/18844
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/brugger1' target='_blank'>brugger1</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/18844' target='_blank'>visit-dav/visit#18844</a>.

<small>The connection progress window is created in `viewer/main/ViewerServerManager.C` in the function `CreateConnectionProgress`. I noticed that the actual creation in the function is within a `#ifdef HAVE_THREADS` block so perhaps `HAVE_THREADS` isn't defined....</small>

<a href='https://github.com/visit-dav/visit/issues/18844' target='_blank'>View Comment</a>