---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/117319280?"
user: queen333597
date: 2022-11-09
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3300
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/queen333597' target='_blank'>queen333597</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3300' target='_blank'>mfem/mfem#3300</a>.

<small>Thank you for your answer. My force is independent of the unknown, so I created a `LinearForm *F` that includes the force (similar to `LinearFrom *b`above). I tried adding it to the right-hand side by adding `z.Add(1.0, F);` to either the `HyperelasticOperator` class or `HyperelasticOperator::Mult` (in example 10), but none of those affects the results. Would you guide me more about where `F` must be added?...</small>

<a href='https://github.com/mfem/mfem/issues/3300' target='_blank'>View Comment</a>