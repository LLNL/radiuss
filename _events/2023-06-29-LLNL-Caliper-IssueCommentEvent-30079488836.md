---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2023-06-29
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/issues/476
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> commented on issue <a href='https://github.com/LLNL/Caliper/issues/476' target='_blank'>LLNL/Caliper#476</a>.

<small>Hi @adayton1, the service class gets one object for each Caliper channel where it's active, but there is typically only one. In fact it doesn't make sense to have a binding service active multiple times. The on_begin/on_end functions can be invoked from multiple threads depending on how the target code is instrumented, so yes a good implementation should make sure to be thread safe. And yes, Caliper does check if the regions match with the CALI_MARK_BEGIN/END macros and error out if they don't....</small>

<a href='https://github.com/LLNL/Caliper/issues/476' target='_blank'>View Comment</a>