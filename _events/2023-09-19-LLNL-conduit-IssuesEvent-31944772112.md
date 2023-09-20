---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/48997041?"
user: agcapps
date: 2023-09-19
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1166
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/agcapps' target='_blank'>agcapps</a> open issue <a href='https://github.com/LLNL/conduit/issues/1166' target='_blank'>LLNL/conduit#1166</a>.

<p>coordset::generate_strip should work for 1D explicit meshes</p><small>User Ryan Bleile reports that `coordset::generate_strip()` only works for uniform or rectilinear coordsets.  Explicit coordsets decay to rectilinear, but the function (see https://github.com/LLNL/conduit/blob/a6b0b179716eb804a0749cc20083c24c21ed682b/src/libs/blueprint/conduit_blueprint_mesh.cpp#L3933) throws an error when Ryan passed it an explicit coordset....</small><a href='https://github.com/LLNL/conduit/issues/1166' target='_blank'>View Comment</a>