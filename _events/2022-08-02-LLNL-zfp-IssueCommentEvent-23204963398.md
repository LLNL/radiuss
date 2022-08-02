---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2022-08-02
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/163
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/163' target='_blank'>LLNL/zfp#163</a>.

<small>@henryleberre I can't think off the top of my head why possible lack of `c_ptrdiff_t` support would interfere with the execution policy, but admittedly we do not yet have adequate testing of the Fortran bindings.  Come to think of it, we recently (around June 22) changed the `zfp_stream` struct on `develop` to separate out the execution parameters to a dynamically allocated struct (pointed to by `void*`).  It's possible that this may have had unintended consequences for the Fortran API, but your issue precedes that change.  Let us take a closer look over the coming days and get back to you. ...</small>

<a href='https://github.com/LLNL/zfp/issues/163' target='_blank'>View Comment</a>