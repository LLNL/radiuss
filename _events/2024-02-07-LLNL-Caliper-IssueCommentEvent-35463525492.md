---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2024-02-07
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/issues/530
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> commented on issue <a href='https://github.com/LLNL/Caliper/issues/530' target='_blank'>LLNL/Caliper#530</a>.

<small>Hi @alkino, yes with the timer resolution increase we added a `.ns` to some of the internal time attribute names like `time.offset` and `time.duration`. This is handled transparently in the built-in config recipes like `hatchet-region-profile`, however if you're manually configuring Caliper with the `CALI_SERVICES_ENABLE` etc. variables and use cali-query to process the output you might need to make these adjustments. Apologies for the inconvenience!...</small>

<a href='https://github.com/LLNL/Caliper/issues/530' target='_blank'>View Comment</a>