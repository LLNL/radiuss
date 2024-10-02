---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/21321692?"
user: publixsubfan
date: 2024-10-01
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/pull/1434
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/publixsubfan' target='_blank'>publixsubfan</a> commented on issue <a href='https://github.com/LLNL/axom/pull/1434' target='_blank'>LLNL/axom#1434</a>.

<small>@rhornung67: I think we'd need to test with asan/ubsan enabled in order to reliably capture a problem like this. Alternatively, `-Weffc++` on Clang might be able to statically warn about uninitialized variables, but it might also spit out a bunch of other warnings that we'd have to work through....</small>

<a href='https://github.com/LLNL/axom/pull/1434' target='_blank'>View Comment</a>