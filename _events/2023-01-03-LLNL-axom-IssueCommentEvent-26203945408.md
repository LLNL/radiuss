---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/21321692?"
user: publixsubfan
date: 2023-01-03
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/issues/986
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/publixsubfan' target='_blank'>publixsubfan</a> commented on issue <a href='https://github.com/LLNL/axom/issues/986' target='_blank'>LLNL/axom#986</a>.

<small>Hi Alan, I looked at ArrayBase.hpp and I believe switching from `#if defined(AXOM_GPUCC)` to `#if defined(AXOM_USE_RAJA) && defined(AXOM_USE_CUDA)` should fix your first issue with CUDA enabled for the application, but disabled for Axom....</small>

<a href='https://github.com/LLNL/axom/issues/986' target='_blank'>View Comment</a>