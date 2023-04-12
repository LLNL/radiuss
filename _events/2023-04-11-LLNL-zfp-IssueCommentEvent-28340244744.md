---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2023-04-11
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/pull/204
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/pull/204' target='_blank'>LLNL/zfp#204</a>.

<small>Thanks for catching this.  Not being a Fortran programmer, I imagine that similar changes ought to be made throughout the zFORp API.  For example, the `zFORp_field_set_size` functions use the same pass-by-reference convention, and I wonder why they would not invoke similar behavior (perhaps because `c_ptrdiff_t` is an extension?).  Indeed, it is surprising that pass-by-reference could result in a segmentation fault since the Fortran wrapper just hands off the argument to the corresponding C function by value.  Before we make a hundred or so changes to handle this consistently, it would be nice to know what's actually going wrong here....</small>

<a href='https://github.com/LLNL/zfp/pull/204' target='_blank'>View Comment</a>