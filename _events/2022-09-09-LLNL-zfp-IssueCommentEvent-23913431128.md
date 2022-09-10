---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/406118?"
user: jeffhammond
date: 2022-09-09
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/163
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/jeffhammond' target='_blank'>jeffhammond</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/163' target='_blank'>LLNL/zfp#163</a>.

<small>What I tried to say before is, I do not think you can overflow when Fortran passes `INTEGER(kind=c_size_t)` to a `ptrdiff_t` because there is no way for Fortran to access the last bit of the positive range, because Fortran doesn't support unsigned integers.  But also, I'm suggesting you only do this -- or `INTEGER(kind=c_int64_t)` -- with a preprocess guard for NVHPC Fortran, which only supports 64-bit Linux right now....</small>

<a href='https://github.com/LLNL/zfp/issues/163' target='_blank'>View Comment</a>