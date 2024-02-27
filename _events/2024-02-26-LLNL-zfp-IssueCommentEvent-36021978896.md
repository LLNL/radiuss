---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2024-02-26
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/228
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/228' target='_blank'>LLNL/zfp#228</a>.

<small>I'm afraid we didn't have time to work out (de)serialization with the `const_array` classes for the 1.0.x releases, but it is likely that this will be supported in the next release.  We have to deal with the same issue to support parallel variable-rate decompression, where we need to quickly locate any given block in the compressed stream.  We're essentially using the same block offset coding strategy for that.  Because we cannot embed these block offsets in the compressed stream while retaining backwards compatibility, we need for the block index to be stored separately, and we're currently working on support for (de)serializing this auxiliary data....</small>

<a href='https://github.com/LLNL/zfp/issues/228' target='_blank'>View Comment</a>