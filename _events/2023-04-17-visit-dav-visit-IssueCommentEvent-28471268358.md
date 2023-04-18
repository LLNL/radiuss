---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2023-04-17
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/18646
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/18646' target='_blank'>visit-dav/visit#18646</a>.

<small>We were just having a dialog about this in email within the last couple of weeks and I've completed preliminary changes to support that. But, there are other issues with displaying the result on a "curve" mesh (which is what the `revolved_volume` expression would have to do) because we currently treat curves *specially* in VisIt and, in particular, they do not support zone-centered values (#18602) wold have to be addressed first because revolved_volume is generate a value per line-segement, not per-node....</small>

<a href='https://github.com/visit-dav/visit/issues/18646' target='_blank'>View Comment</a>