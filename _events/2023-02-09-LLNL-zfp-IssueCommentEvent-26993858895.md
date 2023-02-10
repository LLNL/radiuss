---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-02-09
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/144
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/144' target='_blank'>LLNL/zfp#144</a>.

<small>@pkoosha FYI, the double precision HIP performance on the `staging` branch (soon to be merged into `develop`) has been substantially improved by reducing register spillage.  Currently decode performance on an AMD MI250X consistently outperforms NVIDIA V100, even though the `staging` implementation uses thread blocks of size 32 that do not align well with AMD hardware.  We will remove this limitation to allow larger thread blocks, which will further help AMD performance.  Below is a recent performance plot for one particular 3D data set.  We've seen encode performance reach 800 GB/s on NVIDIA A100, so there's still room for improvement, but the situation is far better than it was....</small>

<a href='https://github.com/LLNL/zfp/issues/144' target='_blank'>View Comment</a>