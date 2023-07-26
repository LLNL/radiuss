---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2023-07-25
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/38776
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> commented on issue <a href='https://github.com/spack/spack/pull/38776' target='_blank'>spack/spack#38776</a>.

<small>I'm not very familiar with building on Windows so any input is appreciated. Searching around a bit this seems to be a Windows issue rather than a ninja problem (the static .lib library conflicting with the shared library's .lib import library?). If it's necessary to install shared and static libraries simultaneously, perhaps we could use [CMAKE_<CONFIG>_POSTFIX](https://cmake.org/cmake/help/latest/variable/CMAKE_CONFIG_POSTFIX.html) to address this?  ...</small>

<a href='https://github.com/spack/spack/pull/38776' target='_blank'>View Comment</a>