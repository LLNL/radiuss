---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2024-08-19
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/241
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/241' target='_blank'>LLNL/zfp#241</a>.

<small>I believe this should be fixed in zfp, as valid input data should never invoke UB.  This is somewhat different from #242, where the user violates zfp's assumptions on all-numerical inputs.  I'm, however, unsure about the best path forward.  My sense is that we need to do some work to prove that any one of the suggested changes above is guaranteed to avoid UB, but it will take some time.  Fortunately we have very smart people at LLNL working on exactly such correctness problems, and I'm hoping we can solicit their help....</small>

<a href='https://github.com/LLNL/zfp/issues/241' target='_blank'>View Comment</a>