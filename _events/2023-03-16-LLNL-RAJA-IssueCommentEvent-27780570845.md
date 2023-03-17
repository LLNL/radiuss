---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12800412?"
user: rhornung67
date: 2023-03-16
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1459
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rhornung67' target='_blank'>rhornung67</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1459' target='_blank'>LLNL/RAJA#1459</a>.

<small>@cyrush thanks for the info. Although it's not perfect, our system of naming each test file attempts to make clear what RAJA features are being tested. Our tests are highly parametrized where we minimize the amount of test code we maintain and specialize based on features that are tested by generating files during CMake configuration. It helps preserve our sanity, but clearly we did not think about name length constraints in different environments. This will require some mulling to resolve....</small>

<a href='https://github.com/LLNL/RAJA/issues/1459' target='_blank'>View Comment</a>