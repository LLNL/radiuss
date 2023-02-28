---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11756601?"
user: brendankeith
date: 2023-02-27
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3511
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/brendankeith' target='_blank'>brendankeith</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3511' target='_blank'>mfem/mfem#3511</a>.

<small>@ricgross I looked again at this once I got to the office. I think your problem may be that you didn't run on a fine enough mesh. Generally, you will need a finer mesh if you want to use a lowest-order discretization. Also, keep in mind that many MFEM features are designed for high-order discretizations, so it is possible that you will see better performance with high-order topology optimization in MFEM than you are used to in other codes. If you see any performance issues with high-order TO in MFEM please let me know....</small>

<a href='https://github.com/mfem/mfem/issues/3511' target='_blank'>View Comment</a>