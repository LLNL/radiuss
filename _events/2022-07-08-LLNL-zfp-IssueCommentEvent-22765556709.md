---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/24208000?"
user: henryleberre
date: 2022-07-08
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/163
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/henryleberre' target='_blank'>henryleberre</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/163' target='_blank'>LLNL/zfp#163</a>.

<small>Update: I looked into it some more today, intercepting the calls in Fortran and in C. Calling `zFORp_stream_set_execution`, the received arguments (in the Fortran interface) are correct but, when they are forwarded to C, I receive nonsensical values. Reinterpreting them as uint64_t as looking at their binary representation doesn't provide more insight. The size of `c_int` and the types representing the enums are the same in C and Fortran....</small>

<a href='https://github.com/LLNL/zfp/issues/163' target='_blank'>View Comment</a>