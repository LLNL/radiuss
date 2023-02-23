---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2023-02-23
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/987
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/987' target='_blank'>flux-framework/flux-sched#987</a>.

<small>I've confirmed that by manipulating the `at` time in `dfu_traverser_t::run`: https://github.com/flux-framework/flux-sched/blob/35d3c96bb7378ec4f6803a7e340043fd4040e8c1/resource/traversers/dfu.cpp#L277 we can achieve the desired behavior. Here I've simulated this by hardcoding `at = 3600` in `dfu_traverser_t::run` and performing a `match allocate`:...</small>

<a href='https://github.com/flux-framework/flux-sched/issues/987' target='_blank'>View Comment</a>