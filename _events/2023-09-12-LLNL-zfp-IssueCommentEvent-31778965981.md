---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-09-12
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/213
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/213' target='_blank'>LLNL/zfp#213</a>.

<small>This seems like some kind of misconfiguration with your environment, with a weird interaction between gcc and pgi, rather than an issue with zfp.  Based on the error you're seeing, it's possible that you can get around the error by disabling OpenMP by adding `-DZFP_WITH_OPENMP=OFF` to your CMake line.  You might also try a google search on the error....</small>

<a href='https://github.com/LLNL/zfp/issues/213' target='_blank'>View Comment</a>