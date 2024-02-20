---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1304791?"
user: lindstro
date: 2024-02-20
repo_name: LLNL/zfp
html_url: https://github.com/LLNL/zfp/pull/226
repo_url: https://github.com/LLNL/zfp
---

<a href='https://github.com/lindstro' target='_blank'>lindstro</a> commented on issue <a href='https://github.com/LLNL/zfp/pull/226' target='_blank'>LLNL/zfp#226</a>.

<small>Thanks for the suggestion.  This might be a good idea, but it would have to be done portably.  I believe this attribute (and `-Wimplicit-fallthrough`) is not supported prior to gcc 7, and presumably there are compilers other than MSVC that don't recognize it.  In C++17, it's `[[fallthrough]]`.  I would prefer some macro mechanism that can be applied to both C and C++ code.  Maybe add a `fallthrough_` macro to `include/zfp/internal/zfp/system.h`?...</small>

<a href='https://github.com/LLNL/zfp/pull/226' target='_blank'>View Comment</a>