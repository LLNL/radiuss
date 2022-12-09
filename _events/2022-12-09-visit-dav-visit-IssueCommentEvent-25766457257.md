---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2022-12-09
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/pull/18366
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/pull/18366' target='_blank'>visit-dav/visit#18366</a>.

<small>Ok, I've adjusted implementation so that the *last* error can only ever by cleared by the CLI calling `GetLastError(int-arg)` with non-zero integer argument. In particular, no where does VisIt internally itself call `ClearErrorMessage()` meaning the the last error ever generated no matter how distant in the past, remains held (assuming no other new error overwrites it) until CLI caller calls `GetLastError(int-arg)` with non-zero integer argument....</small>

<a href='https://github.com/visit-dav/visit/pull/18366' target='_blank'>View Comment</a>