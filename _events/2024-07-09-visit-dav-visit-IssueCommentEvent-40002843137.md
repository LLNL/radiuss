---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1102718?"
user: brugger1
date: 2024-07-09
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/19598
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/brugger1' target='_blank'>brugger1</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/19598' target='_blank'>visit-dav/visit#19598</a>.

<small>I found that the way that VTK 9 handles transparency has changed and that is the cause of the transparency issues we are seeing with scalable rendering. It used to do straight alpha blending as described above with the assumption that the geometry was sorted. They have switched to a new method that leverages some of the depth peeling functionality to allow the geometry to be unsorted. Unfortunately, the alpha values it generates are different, which messes up our scalable rendering....</small>

<a href='https://github.com/visit-dav/visit/issues/19598' target='_blank'>View Comment</a>