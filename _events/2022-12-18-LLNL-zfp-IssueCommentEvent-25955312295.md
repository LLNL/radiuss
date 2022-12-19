---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2022-12-18
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/193
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/193' target='_blank'>LLNL/zfp#193</a>.

<small>@markcmiller86 This looks interesting but I'm not sure how to best expose zfp through such an API since zfp fundamentally operates on multidimensional arrays, whereas the API seems geared toward streams of numbers.  The I/O stream would somehow have to know about array dimensions and/or strides for this to work well.  There's a similar problem of specifying compression settings, e.g., error tolerance.  I've not had a chance to take a close enough look at  the I/O library to see if there's an easy way to incorporate that.  Perhaps one could use something similar to the C++ stream manipulators like `std::set_precision()` to specify compression settings and array metadata....</small>

<a href='https://github.com/LLNL/zfp/issues/193' target='_blank'>View Comment</a>