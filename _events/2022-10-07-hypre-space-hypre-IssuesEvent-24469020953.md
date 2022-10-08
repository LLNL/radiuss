---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2022-10-07
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/667
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> closed issue <a href='https://github.com/hypre-space/hypre/issues/667' target='_blank'>hypre-space/hypre#667</a>.

<p>Include contents of ams.h in _hypre_parcsr_ls.h</p><small>I'd like to modify the build process so that the contents of `ams.h` get added to `_hypre_parcsr_ls.h` (just as `par_amg.h`) appears got be copied over. My real goal is to be able to read properties of the AMS solver (either through the macros like `hypre_AMSDataDimension` or just by direct accessing the fields of the struct). An alternative would be to write proper `HYPRE_AMSGet*` functions (like those that exist for BoomerAMG)....</small><a href='https://github.com/hypre-space/hypre/issues/667' target='_blank'>View Comment</a>