---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2024-02-23
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/b2876422b4ef36bcfe80bede57962b4332c01a07
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Fix windows compile errors. (#19344) (#19345)

vtkIdType cverts[nbnel] yields 'does not evaluate to constant' error.
In order for this to work 'nbnel' must be a constant at compile time, so need to use 'new' to allocate the array.

strcasestr not defined on Windows, #define it to be 'StrStrIA'.</small>

<a href='https://github.com/visit-dav/visit/commit/b2876422b4ef36bcfe80bede57962b4332c01a07' target='_blank'>View Commit</a>