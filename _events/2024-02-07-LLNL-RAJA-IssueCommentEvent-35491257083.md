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

<small>That compile command doesn't include the flag, what are you testing here?  My first guess as to the cause is maybe nvcc is reading the wrong OpenMP headers, the gcc libgomp headers rather than the clang libomp headers, and clang is loading its own.  Then again if you use `xl` or `clang-ibm` then they are set up to use `lomp`, the IBM runtime, which has yet another set of headers.  If in any of these nvcc gets a different set of headers in pre-processing than clang or xl does, it will likely break either in compilation, because the declarations aren't portable, or linking when the symbols don't match up....</small>

<a href='https://github.com/LLNL/RAJA/issues/1595' target='_blank'>View Comment</a>