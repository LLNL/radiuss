---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1102718?"
user: brugger1
date: 2022-11-04
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/18196
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/brugger1' target='_blank'>brugger1</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/18196' target='_blank'>visit-dav/visit#18196</a>.

<small>Specifying the CRAY compilers as the C and C++ compilers appears to fix the issues with the compiler wrappers. The only issue is that the mili configure script uses specific compiler names that it recognizes for passing along arguments. The absolute path to a CRAY compilers is not one of them. We should modify our patch to add an else case that passes along arguments. This is critical for building mili since we specify `-fPIC` in the arguments, which is needed for VisIt to be able to link the library....</small>

<a href='https://github.com/visit-dav/visit/issues/18196' target='_blank'>View Comment</a>