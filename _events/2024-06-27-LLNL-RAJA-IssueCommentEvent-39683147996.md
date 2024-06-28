---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/25917313?"
user: mdavis36
date: 2024-06-27
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1687
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/mdavis36' target='_blank'>mdavis36</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1687' target='_blank'>LLNL/RAJA#1687</a>.

<small>@rhornung67 FWIW This looks correct to me, we have to use CURRENT in our submodule structure. CMake tries to use the root directory of the "master" project and will not reference the root directory of a given submodule so using the CURRENT variant of these variables is a safer way of doing this....</small>

<a href='https://github.com/LLNL/RAJA/pull/1687' target='_blank'>View Comment</a>