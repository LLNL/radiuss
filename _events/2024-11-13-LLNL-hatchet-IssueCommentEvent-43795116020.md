---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/28907237?"
user: ilumsden
date: 2024-11-13
repo_name: LLNL/hatchet
html_url: https://github.com/LLNL/hatchet/pull/152
repo_url: https://github.com/LLNL/hatchet
---

<a href='https://github.com/ilumsden' target='_blank'>ilumsden</a> commented on issue <a href='https://github.com/LLNL/hatchet/pull/152' target='_blank'>LLNL/hatchet#152</a>.

<small>To clarify, the reason we need `multi_index_mode`/`predicate_row_aggregator` is because the graph algorithm-part of the query language needs predicates to provide a single boolean for each node. When we do not have a row `MultiIndex` (i.e., the standard case for Hatchet), this requirement is always satisfied. However, when we do have a row `MultiIndex` (i.e., the standard case for Thicket), this requirement is never satisfied because we have multiple rows in the `DataFrame` per node. As a result, predicates will return a `pandas.Series` of booleans when we have a row `MultiIndex`. The `multi_index_mode`/`predicate_row_aggregator` argument provides a mechanism to aggregate that `Series` of booleans into a single boolean....</small>

<a href='https://github.com/LLNL/hatchet/pull/152' target='_blank'>View Comment</a>