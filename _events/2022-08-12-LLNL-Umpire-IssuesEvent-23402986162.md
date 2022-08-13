---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/42977?"
user: msimberg
date: 2022-08-12
repo_name: LLNL/Umpire
html_url: https://github.com/LLNL/Umpire/issues/771
repo_url: https://github.com/LLNL/Umpire
---

<a href='https://github.com/msimberg' target='_blank'>msimberg</a> open issue <a href='https://github.com/LLNL/Umpire/issues/771' target='_blank'>LLNL/Umpire#771</a>.

<p>`std::filesystem` incorrectly detected</p><small>I think the check for `std::filesystem` is currently insufficient. GCC 11 updated the default C++ standard to 17. When the check is done no C++ standard flags are passed to the compilation which makes it use the default of 17 and it concludes that `std::filesystem` is available. However, the default `BLT_CXX_STD` is C++14, which makes compilation then fail because `std::filesystem` isn't available in C++14 mode....</small><a href='https://github.com/LLNL/Umpire/issues/771' target='_blank'>View Comment</a>