---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2023-06-29
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/942
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/942' target='_blank'>hypre-space/hypre#942</a>.

<small>Hi @ulrikeyang .  This looks great modulo the comments!  It looks like a significant part of the work you did was related to this `rtol` thing (set by calling `HYPRE_PCGSetResidualTol`).  This is only available in PCG and only used by the AMS driver.  The documentation for it in `HYPRE_krylov.h` says it's "useful when trying to converge to very low tolerances, in order to bail-out before roundoff errors affect the approximation".  This is something we care about, but I'm not sure this is the right way to do it or if anybody even uses it.  If it's useful, we should add it to the other Krylov routines as well.  If not, maybe we should remove it altogether (in a future PR).  Sounds like an agenda item for our meeting. :)...</small>

<a href='https://github.com/hypre-space/hypre/pull/942' target='_blank'>View Comment</a>