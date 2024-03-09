---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2024-03-09
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/db217520c012eef5995a6a85fb799f2ae0706bd9
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Fix python modules windows (#19360) (#19362)

* Fix visit's python module handling on Windows.

The DEST_DIR should be /path/to/build/lib/<CONFIG>/site-packages.
So, removed the 'lib/' part from DEST_DIR in calls to PYTHON_ADD_PIP_SETUP, and modified the function to use VISIT_LIBRARY_DIR instead of CMAKE_BINARY_DIR, as VISIT_LIBRARY_DIR accounts for the <CONFIG> part of the library path on Windows.

Modified VISIT_LIBRARY_DIR setup for Windows to use $<CONFIG> instead of ${CMAKE_CFG_INTDIR}, which has been deprecated.

* Add logic to cleanup `pip install`  build artifacts left in source.</small>

<a href='https://github.com/visit-dav/visit/commit/db217520c012eef5995a6a85fb799f2ae0706bd9' target='_blank'>View Commit</a>