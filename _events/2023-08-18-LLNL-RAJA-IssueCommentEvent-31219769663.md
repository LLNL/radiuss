---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12800412?"
user: rhornung67
date: 2023-08-18
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1536
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/rhornung67' target='_blank'>rhornung67</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1536' target='_blank'>LLNL/RAJA#1536</a>.

<small>Not a known issue for us on our MI250x systems. It looks like the error arises during the compilation of one of the RAJA tutorial exercise codes (atomic_histogram_solution). My guess is that you don't need to build those. Please try passing the option `-DRAJA_ENABLE_EXERCISES=Off` to CMake when you configure RAJA....</small>

<a href='https://github.com/LLNL/RAJA/issues/1536' target='_blank'>View Comment</a>