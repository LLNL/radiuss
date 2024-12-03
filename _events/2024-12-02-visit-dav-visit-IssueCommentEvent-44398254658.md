---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2024-12-02
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/19244
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/19244' target='_blank'>visit-dav/visit#19244</a>.

<small>@biagas...thanks for pointing this out. Its a subtle difference that should be corrected. One is pre-caching global node ids for a point mesh in case they are ever asked for. The other issue (the one your are describing here) is if for some reason global node ids are not pre-cached for a point mesh (I can't imagine why that might happen), then they are never obtained via this more explicit route. I have reopened and moved to 3.4.3. The right action for 3.4.3 may be to just close this again after confirming that the path you describe cannot happen....</small>

<a href='https://github.com/visit-dav/visit/issues/19244' target='_blank'>View Comment</a>