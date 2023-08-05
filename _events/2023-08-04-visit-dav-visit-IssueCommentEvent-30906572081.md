---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1102718?"
user: brugger1
date: 2023-08-04
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/18549
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/brugger1' target='_blank'>brugger1</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/18549' target='_blank'>visit-dav/visit#18549</a>.

<small>The function `GetQueryOutputValue` now returns `None` if the query returns no values. This could be used to determine if an error occurred. This won't work in the case of the "XRay Image" query since it always returns no values and hence `None` for `GetQueryOutputValue`. It could be changed to return no values if the query fails and the number of files generated in the case of success. In general, all the queries would need to be checked to ensure that they return no values in the case of an error for this to be universally applicable....</small>

<a href='https://github.com/visit-dav/visit/issues/18549' target='_blank'>View Comment</a>