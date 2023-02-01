---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/49128971?"
user: aavbsouza
date: 2023-02-01
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/199
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/aavbsouza' target='_blank'>aavbsouza</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/199' target='_blank'>LLNL/zfp#199</a>.

<small>Hello @lindstro the original motivation for the issue was a segmentation fault on a code when running in parallel (with oneapi::tbb), the snippet used on this thread is based on a pattern that appear on this code. Others sections of this same  code I was able to run with thread sanitize enabled without generating false positives. However the section in that code that is similar to the above snippet when executed with the thread sanitize enabled presents the same kind of errors show on this thread. And the problem only manifests if the parallelism is enabled. ...</small>

<a href='https://github.com/LLNL/zfp/issues/199' target='_blank'>View Comment</a>