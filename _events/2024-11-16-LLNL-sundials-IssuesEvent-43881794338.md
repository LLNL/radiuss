---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/485936?"
user: bjodah
date: 2024-11-16
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/229
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/bjodah' target='_blank'>bjodah</a> closed issue <a href='https://github.com/LLNL/sundials/issues/229' target='_blank'>LLNL/sundials#229</a>.

<p>Default of SUNDIALS_MATH_LIBRARY incorrect?</p><small>I'm updating a build script for sundials and I got some linking errors related to transitioning from USE_GENERIC_MATH to `SUNDIALS_MATH_LIBRARY`. I noticed that the default value for SUNDIALS_MATH_LIBRARY gets set to `"-lm"`, I think it should read just `"m"` shouldn't it? But maybe CMake strips leading `-l`, I haven't actually confirmed that it matters....</small><a href='https://github.com/LLNL/sundials/issues/229' target='_blank'>View Comment</a>