---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/21321692?"
user: kanye-quest
date: 2022-08-03
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/pull/887
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/kanye-quest' target='_blank'>kanye-quest</a> commented on issue <a href='https://github.com/LLNL/axom/pull/887' target='_blank'>LLNL/axom#887</a>.

<small>Spitballing here: could we use `ExternalProject_Add()` in lieu of `add_subdirectory()`? I think that'd let us independently build and install our submodule TPLs without pulling stuff into the axom cmake context. Then we could just add it like any other TPL with `find_package()`....</small>

<a href='https://github.com/LLNL/axom/pull/887' target='_blank'>View Comment</a>