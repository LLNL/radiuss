---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-02-24
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/200
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/200' target='_blank'>LLNL/zfp#200</a>.

<small>The issue here is that zfp has to conservatively estimate how much space is needed for the compressed data and must allow for the worst-case input.  Since it knows nothing about the data that is to be compressed, it has to make this very pessimistic assumption.  Due to the pigeonhole principle, any compressor must expand some inputs, and in this case that worst-case expansion leads to an estimate of 49 MB, slightly larger than the uncompressed input.  Because your data is quite compressible, you're seeing a much smaller compressed size in practice, as is to be expected.  One way to mitigate this overallocation is to use C `malloc()` and `realloc()` to (re)allocate the memory buffer and relinquish any unused memory....</small>

<a href='https://github.com/LLNL/zfp/issues/200' target='_blank'>View Comment</a>