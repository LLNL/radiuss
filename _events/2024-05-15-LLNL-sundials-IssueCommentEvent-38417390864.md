---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2024-05-15
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/pull/477
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/LLNL/sundials/pull/477' target='_blank'>LLNL/sundials#477</a>.

<small>If we want to ensure that other LLP64 and ILP32 systems can use SuiteSparse < 6 and 64-bit SUNDIALS_INDEX_SIZE together, then we can add a check of the SuiteSparse version in a preprocessor macro.  I actually don't think it would be possible for an ILP32 system to run into the issue because they would probably not be using SUNDIALS_INDEX_SIZE=64, and I don't know of any non Windows LLP64 systems. ...</small>

<a href='https://github.com/LLNL/sundials/pull/477' target='_blank'>View Comment</a>