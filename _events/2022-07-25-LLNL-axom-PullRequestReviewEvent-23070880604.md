---
event_type: PullRequestReviewEvent
avatar: "https://avatars.githubusercontent.com/u/48997041?"
user: agcapps
date: 2022-07-25
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/pull/868#pullrequestreview-1039327475
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/agcapps' target='_blank'>agcapps</a> <a href='https://github.com/LLNL/axom/pull/868#pullrequestreview-1039327475' target='_blank'>reviewed</a> a <a href='https://github.com/LLNL/axom/pull/868' target='_blank'>LLNL/axom pull request</a>

<small>As I noted in slic_macros.hpp, if you call `slic::locErrorMessage()` it calls `ensureInitialized()` for you.  So you don't need to test `isInitialized()` to call `abortIfEnabled()`.  Also, as in `SLIC_ERROR_IF`, I think the call to `abortIfEnabled` should go inside the braces after `logErrorMessage()`....</small>

<a href='https://github.com/LLNL/axom/pull/868#pullrequestreview-1039327475' target='_blank'>View Review</a>