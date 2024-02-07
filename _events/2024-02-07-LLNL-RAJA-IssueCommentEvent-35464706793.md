---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-02-07
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1595
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1595' target='_blank'>LLNL/RAJA#1595</a>.

<small>First thing here, it isn't a linker error.  This is an error caused by the C++ linkage specification being different between two different declarations in the same translation unit while compiling.  Normally with clang that would print the source locations of both declarations.  My guess would be the situation is two different headers, one that has `int omp_is_initial_device();` and one that has `inline int omp_is_initial_device();` (inline requires different linkage, hence the error) or similar.  If you can repro this with just clang and not nvcc, you'll get a _much_ better error message....</small>

<a href='https://github.com/LLNL/RAJA/issues/1595' target='_blank'>View Comment</a>