---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/123136?"
user: rountree
date: 2024-11-04
repo_name: hpc/Spindle
html_url: https://github.com/hpc/Spindle/pull/56
repo_url: https://github.com/hpc/Spindle
---

<a href='https://github.com/rountree' target='_blank'>rountree</a> commented on issue <a href='https://github.com/hpc/Spindle/pull/56' target='_blank'>hpc/Spindle#56</a>.

<small>Point taken wrt scaling and file pollution.  I can imagine a solution where messages (with their priority) are buffered until initialization occurs, then parsed to see if they're logged or discarded.  It's not wholly unlike trying to make `printf()` work in `_start()` before your file descriptors are set up, and, perhaps like that, it's not a problem worth solving (or not worth solving this week)....</small>

<a href='https://github.com/hpc/Spindle/pull/56' target='_blank'>View Comment</a>