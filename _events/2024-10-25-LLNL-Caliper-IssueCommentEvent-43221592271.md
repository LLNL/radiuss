---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/28907237?"
user: ilumsden
date: 2024-10-25
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/pull/576
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/ilumsden' target='_blank'>ilumsden</a> commented on issue <a href='https://github.com/LLNL/Caliper/pull/576' target='_blank'>LLNL/Caliper#576</a>.

<small>@daboehme I've worked that change into the PR. I did have to make one small change to that mechanism to handle architecture detection. I had to move where `builtin_option_specs_list` gets populated from global scope to the constructor of `ConfigManagerImpl` due to having to do string comparison (which is extremely difficult to do at compile time in C++11)....</small>

<a href='https://github.com/LLNL/Caliper/pull/576' target='_blank'>View Comment</a>