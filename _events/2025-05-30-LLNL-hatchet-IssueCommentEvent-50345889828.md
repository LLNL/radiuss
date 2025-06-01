---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/32579379?"
user: michaelmckinsey1
date: 2025-05-30
repo_name: LLNL/hatchet
html_url: https://github.com/LLNL/hatchet/issues/162
repo_url: https://github.com/LLNL/hatchet
---

<a href='https://github.com/michaelmckinsey1' target='_blank'>michaelmckinsey1</a> commented on issue <a href='https://github.com/LLNL/hatchet/issues/162' target='_blank'>LLNL/hatchet#162</a>.

<small>@mkre It appears the `cxx-example.cpp` program executes too quickly for the sampler to profile `main` and `mainloop`. The `gf.dataframe` in your profile contains performance information for only `foo`, and the calltree `gf.graph` contains regions `main`, `mainloop`, and `foo`. The `gf.tree()` function prints the performance information alongside the calltree, so it errors because of the missing performance information. See this profile where I added dummy loops to give the sampler time to profile the `main` and `mainloop` missing functions [sample_profile.cali.txt](https://github.com/user-attachments/files/20526879/sample_profile.cali.txt). You can also increase the sampling frequency parameter, however there is a limit on precision....</small>

<a href='https://github.com/LLNL/hatchet/issues/162' target='_blank'>View Comment</a>