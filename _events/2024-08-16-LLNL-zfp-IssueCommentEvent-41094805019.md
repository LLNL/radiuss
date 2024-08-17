---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2024-08-16
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/241
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/241' target='_blank'>LLNL/zfp#241</a>.

<small>Indeed, that looks like a faulty assumption that integer overflow wraps.  One obvious fix would be to use unsigned arithmetic here, though that requires some changes that propagate across a few functions.  I'll see if I can get a fix done in the next few days....</small>

<a href='https://github.com/LLNL/zfp/issues/241' target='_blank'>View Comment</a>