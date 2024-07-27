---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2024-07-26
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/pull/388
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> commented on issue <a href='https://github.com/LLNL/Caliper/pull/388' target='_blank'>LLNL/Caliper#388</a>.

<small>Ouch, okay. Thanks @cyrush for the report. I didn't realize there's a limit on string literals. As a short-term workaround we can simply give MSVC a shorter string with only a few of the options (or nothing at all, depending on what the target app needs). I hope the compiler won't run into this issue if the string is `#ifdef`'d out. Most of the options in there aren't supported on Windows anyway. ...</small>

<a href='https://github.com/LLNL/Caliper/pull/388' target='_blank'>View Comment</a>