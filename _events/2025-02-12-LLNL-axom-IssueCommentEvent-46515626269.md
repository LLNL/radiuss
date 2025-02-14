---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/63525600?"
user: gberg617
date: 2025-02-12
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/pull/1478
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/gberg617' target='_blank'>gberg617</a> commented on issue <a href='https://github.com/LLNL/axom/pull/1478' target='_blank'>LLNL/axom#1478</a>.

<small>Update on the failing tests: The multiple_communicators test I added sporadically fails on Azure.  This test is important to capture certain behavior when multiple communicators are sending/receiving messages.  Looking into this, it sometimes fails when run with other unit tests (and only on Azure), but consistently passes when it is run by itself.  I have heard that gtest+MPI is somewhat fragile in some cases, so I attempted to remove gtest from the tests I added by converting the ASSERT macros to my own version, and having each test become a function that is called within `main()` inside of `lumberjack_NonCollectiveRootCommunicator.cpp`.  This fixes the issue, and both tests in this file always pass.  Does the Axom team have any thoughts about potentially adding unit tests that do not use gtest?  If there is a strong preference for requiring gtest, does anyone have thoughts on other solutions that can prevent these sporadic failures?...</small>

<a href='https://github.com/LLNL/axom/pull/1478' target='_blank'>View Comment</a>