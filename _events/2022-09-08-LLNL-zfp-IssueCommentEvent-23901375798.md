---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2022-09-08
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/163
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/163' target='_blank'>LLNL/zfp#163</a>.

<small>I was commenting on undefined behavior in the context of "all nontrivial C programs contain undefined behavior." :-)  C90 and C99 (which are the standards zfp targets) allow signed integer trap representations, which invoke UB, and representations other than two's complement (as does C11--not sure about C17), though they are of course rare.  To my knowledge, N2218 is still in proposal form and has not been adopted yet.  Hence, it's possible (albeit very unlikely) that UB would occur with `size_t` and `ptrdiff_t` conversions.  Conversion from `size_t` to `ptrdiff_t` can also result in overflow, which is implementation defined....</small>

<a href='https://github.com/LLNL/zfp/issues/163' target='_blank'>View Comment</a>