---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/21321692?"
user: publixsubfan
date: 2024-11-13
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/issues/1464
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/publixsubfan' target='_blank'>publixsubfan</a> commented on issue <a href='https://github.com/LLNL/axom/issues/1464' target='_blank'>LLNL/axom#1464</a>.

<small>I did a cursory investigation and was able to reproduce the issue in ROCM 6.1.2 but not ROCM 6.2.1. Based on experience with another project, we may be able to add in `-mllvm -amdgpu-legacy-sgpr-spill-lowering=true` to mitigate this. But I need to figure out how to pass this in for Axom - the flag I was using to pass in that flag (`-Xoffload-linker`) is being ignored with amdclang....</small>

<a href='https://github.com/LLNL/axom/issues/1464' target='_blank'>View Comment</a>