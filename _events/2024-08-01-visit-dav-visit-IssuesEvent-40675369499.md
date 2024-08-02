---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2024-08-01
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/19104
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> closed issue <a href='https://github.com/visit-dav/visit/issues/19104' target='_blank'>visit-dav/visit#19104</a>.

<p>Building IceT on kickit fails with cmake first time around.</p><small>I was running `build_visit` on kickit and it failed executing `cmake` when building IceT. On kickit, there is a `gcc` installed in a non-standard location, so the `LD_LIBRARY_PATH` is set appropriately. When it builds VTK, `cmake` runs fine, but by the time it gets to IceT, it fails because it is getting the wrong standard C++ library. If I run `build_visit` a second time IceT builds successfully. My thought is that something gets messed up for `cmake` to run building one of the packages. On the second time through, it has already built the bad package and so `cmake` runs properly when building IceT....</small><a href='https://github.com/visit-dav/visit/issues/19104' target='_blank'>View Comment</a>