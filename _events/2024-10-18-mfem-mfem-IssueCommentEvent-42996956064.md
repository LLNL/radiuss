---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2421912?"
user: helloworld922
date: 2024-10-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4523
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/helloworld922' target='_blank'>helloworld922</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4523' target='_blank'>mfem/mfem#4523</a>.

<small>I figured out what was causing my segfaults, it was how I was building HYPRE. I managed to configure HYPRE with `HYPRE_USING_UNIFIED_MEMORY` and `HYPRE_USING_DEVICE_MEMORY` at the same time. I can submit patches to HYPRE which make doing this impossible....</small>

<a href='https://github.com/mfem/mfem/pull/4523' target='_blank'>View Comment</a>