---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/48997041?"
user: agcapps
date: 2023-04-25
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1110
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/agcapps' target='_blank'>agcapps</a> open issue <a href='https://github.com/LLNL/conduit/issues/1110' target='_blank'>LLNL/conduit#1110</a>.

<p>Make Relay support 3D HDF5 hyperslabs</p><small>Currently, Relay sets the offsets and strides [using only the first element](https://github.com/LLNL/conduit/blob/636c024ffe2a04ce0b68a818f4d65cd355de96bb/src/libs/relay/conduit_relay_io_hdf5.cpp#L2732) of whatever the user passed in.  We should support N-D hyperslabs, that is, whatever the user passes in.  Additionally, we should support element counts in N-D, not just "number of elements."...</small><a href='https://github.com/LLNL/conduit/issues/1110' target='_blank'>View Comment</a>