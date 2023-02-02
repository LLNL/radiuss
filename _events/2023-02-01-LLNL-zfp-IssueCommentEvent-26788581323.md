---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-02-01
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/199
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/199' target='_blank'>LLNL/zfp#199</a>.

<small>From the discussion above, we do expect issues when using zfp with TBB if the code is not compiled with OpenMP enabled.  Do the segmentation faults persist if you compile with `-fopenmp`?  Given that ThreadSanitizer gives false positives for the most basic OpenMP example, I think we cannot rely on it to diagnose data races.  To make further progress, I would need a complete--but minimal--code example that invokes provably erroneous behavior....</small>

<a href='https://github.com/LLNL/zfp/issues/199' target='_blank'>View Comment</a>