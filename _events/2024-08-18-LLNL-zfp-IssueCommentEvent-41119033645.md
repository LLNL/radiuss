---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2024-08-18
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/241
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/241' target='_blank'>LLNL/zfp#241</a>.

<small>It seems we're about to open up Pandora's box.  These UB issues are not confined just to signed integer overflow in the reversible zfp algorithm, but the same can evidently happen in the far more important non-reversible algorithm.  For example, a 1D float block `{ 7.f, 7.f, 7.f, 7.f }` encoded with `maxprec = 2` results in decoded input *x* = 2<sup>30</sup>, *y* = *z* = *w* = 0 to `inv_lift()`:...</small>

<a href='https://github.com/LLNL/zfp/issues/241' target='_blank'>View Comment</a>