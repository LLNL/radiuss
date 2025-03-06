---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2025-03-05
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/1eb23b941ea50a05c8e8f4c9f8ddfa7f1581d1e6
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Fixes for Vs database reader plugin (#20272)

* Vs database plugin - Create a wrapper around the hdf5.h header to set the API version before including the header.  Fixes build against hdf5-1.12.

* Prevent the Vs Plugin from accidentally holding on to a file handle by removing the class member thisData and instead instantiating it for every invocation. That class effectively needs to get reinitialized every time it's used, so there's no particular benefit to keeping it active between invocations. The purpose of this change is to eliminate file-handle conflicts on Windows, where the simulation engine is unable to write updates to data files if they are being actively visualized. This change also adds some new messages to the debugging log for the Vs plugin that specifically denote when a file handle is being opened and released.

* Fix a crash in the Vs database plugin when loading a structured mesh with enough cells to overflow a 32-bit integer field. Switching the variable from int to ssize_t to ensure that we have enough room for larger values, while still allowing the variable to hold a negative value for error signalling and loops that use i--. Also adding a warning message if the NumberCells field of the avtMeshMetaData class overflows the integer field - this is just a warning, not a fatal error, because the VisIt team believes this value is not used anywhere downstream.

* Change the way the Vs database plugin loads axis data for rectilinear meshes, specifically addressing the case where the domain decomposition feature is enabled. The code now loads ALL axis information, and then performs subselection on that data. This change makes the code behavior match the comments in this method. Subselection now happens after the mesh data has been loaded. This fixes a memory-related crash when loading rectilinear meshes on multiple processors.

* Update ignore list to include .DS_Store, which is a MacOS indexing file.

---------

Co-authored-by: John Cary <cary@txcorp.com></small>

<a href='https://github.com/visit-dav/visit/commit/1eb23b941ea50a05c8e8f4c9f8ddfa7f1581d1e6' target='_blank'>View Commit</a>