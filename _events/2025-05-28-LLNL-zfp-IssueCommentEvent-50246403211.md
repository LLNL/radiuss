---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2025-05-28
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/pull/268
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/pull/268' target='_blank'>LLNL/zfp#268</a>.

<small>The purpose of the `stream_rseek` call is to update the `bitstream` state in host memory so that when you return from `zfp_decompress`, the stream is positioned correctly for the next `zfp_decompress` call.  No need to update any device data structures here....</small>

<a href='https://github.com/LLNL/zfp/pull/268' target='_blank'>View Comment</a>