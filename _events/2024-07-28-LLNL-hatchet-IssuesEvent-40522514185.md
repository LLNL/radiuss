---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/28907237?"
user: ilumsden
date: 2024-07-28
repo_name: LLNL/hatchet
html_url: https://github.com/LLNL/hatchet/issues/145
repo_url: https://github.com/LLNL/hatchet
---

<a href='https://github.com/ilumsden' target='_blank'>ilumsden</a> open issue <a href='https://github.com/LLNL/hatchet/issues/145' target='_blank'>LLNL/hatchet#145</a>.

<p>Design of subgraph_sum and subtree_sum leads to very suboptimal performance</p><small>Rule number 1 of any dataframe library is "don't do operations by iterating over rows." However, this is exactly what we do in `subgraph_sum` and `subtree_sum`. We need to refactor this to use a better mechanism (e.g., `DataFrame.apply`)....</small><a href='https://github.com/LLNL/hatchet/issues/145' target='_blank'>View Comment</a>