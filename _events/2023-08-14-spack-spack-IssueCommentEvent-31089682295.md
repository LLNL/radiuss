---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-08-14
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/34926
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/34926' target='_blank'>spack/spack#34926</a>.

<small>At least for us, most of the overhead last I checked was adding clauses one at a time. If that's still the case, the issue wasn't so much the call overhead as it was allocating in python, populating in python, then allocating and translating into C++. If we could bulk-add somehow or directly generate the c++ objects as we go rather than building a python object that's then converted that might be a bigger overall win. Even going back to generating it as a big string and passing it off to clingo might do it TBH. ...</small>

<a href='https://github.com/spack/spack/pull/34926' target='_blank'>View Comment</a>