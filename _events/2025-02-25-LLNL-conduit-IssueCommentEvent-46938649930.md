---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/213514?"
user: eschnett
date: 2025-02-25
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1367
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/eschnett' target='_blank'>eschnett</a> commented on issue <a href='https://github.com/LLNL/conduit/issues/1367' target='_blank'>LLNL/conduit#1367</a>.

<small>I looked at the code, and it seems that conduit is using `std::endl` instead of `\n` everywhere. I don't think that's a good programming guideline. It might be worthwhile changing all `std::endl` to `\n`, and adding explicit calls to `std::flush` where necessary (if necessary at all)....</small>

<a href='https://github.com/LLNL/conduit/issues/1367' target='_blank'>View Comment</a>