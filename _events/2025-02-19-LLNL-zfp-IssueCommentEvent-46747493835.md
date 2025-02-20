---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2025-02-19
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/issues/253
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/issues/253' target='_blank'>LLNL/zfp#253</a>.

<small>As discussed offline, (de)serialization indeed appears broken.  A possible workaround for serialization of a concrete array `arr`  of type `arr_type` (e.g., `zfp::array3<double>`) is to use the derived type `arr_type::header` as header type, or (in C++11) `decltype(arr)::header`.  If `arr_type` is the base class `zfp::array`, one likely would need a switch statement on `arr.scalar_type()` and `arr.dimensionality()` to determine the correct header type....</small>

<a href='https://github.com/LLNL/zfp/issues/253' target='_blank'>View Comment</a>