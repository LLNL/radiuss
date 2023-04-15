---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/34784921?"
user: rchen20
date: 2023-04-14
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1464
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rchen20' target='_blank'>rchen20</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1464' target='_blank'>LLNL/RAJA#1464</a>.

<small>Hi @YohannDudouit, I've tried `-DRAJA_ENABLE_VECTORIZATION=Off` on a couple different builds on LLNL systems, and it seems to remain off. In your build, would you mind checking whether `/* #undef RAJA_ENABLE_VECTORIZATION */` is an existing line in your `build/include/RAJA/config.hpp` file? If the vectorization variable is defined there, could you try removing the entire build directory, and rebuilding again? Perhaps the past builds are affecting your current build, and I'd like to eliminate that possibility by removing the build directory and rebuilding. Thanks!...</small>

<a href='https://github.com/LLNL/RAJA/issues/1464' target='_blank'>View Comment</a>