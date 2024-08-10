---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/28907237?"
user: ilumsden
date: 2024-08-09
repo_name: LLNL/hatchet
html_url: https://github.com/LLNL/hatchet/issues/149
repo_url: https://github.com/LLNL/hatchet
---

<a href='https://github.com/ilumsden' target='_blank'>ilumsden</a> open issue <a href='https://github.com/LLNL/hatchet/issues/149' target='_blank'>LLNL/hatchet#149</a>.

<p>Combining predicates in string dialect can cause errors if IS LEAF is first predicate</p><small>When creating a string dialect predicate consisting of `IS LEAF` followed by other predicates (e.g., `p."name" = "..."`), applying the query will fail because the type check will have a leading Python binary operation (e.g., `and`, `or`)....</small><a href='https://github.com/LLNL/hatchet/issues/149' target='_blank'>View Comment</a>