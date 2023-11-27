---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-11-26
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/218
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/218' target='_blank'>LLNL/zfp#218</a>.

<small>The zfp API currently exposes only host functions.  To do what you want, you should allocate a buffer for the decompressed data using `cudaMalloc` and pass the resulting device pointer to `zfp_field_1d` on the host.  When you later call `zfp_decompress`, zfp will determine if any data movement is needed.  If the compressed data resides on the host, it will first be copied to the device before decompression occurs....</small>

<a href='https://github.com/LLNL/zfp/issues/218' target='_blank'>View Comment</a>