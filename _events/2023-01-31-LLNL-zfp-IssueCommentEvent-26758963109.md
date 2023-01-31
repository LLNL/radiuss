---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-01-31
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/199
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/199' target='_blank'>LLNL/zfp#199</a>.

<small>Yes, but linking is not sufficient--you also need to **compile** your code with `-fopenmp` so that `_OPENMP` is defined and the pragmas in the zfp headers are processed.  Even then, I'm not entirely convinced  that non-OpenMP threads entering the OpenMP critical region will do the right thing, but it's worth a shot....</small>

<a href='https://github.com/LLNL/zfp/issues/199' target='_blank'>View Comment</a>