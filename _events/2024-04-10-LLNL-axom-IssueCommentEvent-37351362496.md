---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2024-04-10
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/issues/1315
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> commented on issue <a href='https://github.com/LLNL/axom/issues/1315' target='_blank'>LLNL/axom#1315</a>.

<small>I'd generally recommend using `cali_begin_region(const char* name)` and `cali_end_region(const char* name)` for marking the regions. The `cali::Caliper` API is considered internal so there's a higher risk of things changing in the future, although it's not very likely here. The `cali_end_region` call checks if the given value matches the top of the Caliper region stack and gives an error if it doesn't. You can do the same with `cali::Caliper::end_with_value_check(const Attribute&, const Variant&)`, which is what `cali_end_region` does under the hood. That said your current version is going to be slightly faster since it skips this check....</small>

<a href='https://github.com/LLNL/axom/issues/1315' target='_blank'>View Comment</a>