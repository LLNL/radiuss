---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2024-06-24
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/53af1a45f0a6f8789ddecb859f9b64d2b25a9120
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Fix qt6 build issues when qt6 on system (#19618) (#19620)

* Modified the builds of qttools and qtsvg to use qt-configure-module for configuring instead of CMake.
There were issues building Qt 6 if there was a version installed on the sytstem.
qttools would pick up some of the qtbase modules from the system instead of using the ones pointed to by Qt6_DIR passed to CMake.

* Add use of Qt6CoreTools_DIR, Qt6GuiTools_DIR, and Qt6WidgetsTools_DIR
to ensure that VTK utilizes only the Qt6 modules from the Qt6 that build_visit points to and not mix with other versions that might be on the system.

* Update release notes with recent fixes to build_visit.</small>

<a href='https://github.com/visit-dav/visit/commit/53af1a45f0a6f8789ddecb859f9b64d2b25a9120' target='_blank'>View Commit</a>