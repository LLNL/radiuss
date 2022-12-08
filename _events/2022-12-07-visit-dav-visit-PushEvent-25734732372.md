---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2022-12-07
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/88b3c39bab528c1912f86c01433f7160a001a0c4
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>CMake reorg phase3 (#18359)

* Remove VISIT_OUT_OF_SOURCE_BUILD

Out of source builds are required, and the check is performed by BLT.

* Consolidate parallel settings/functions into VisItParallel.cmake.

* Fix typo.

* Add VisItFunctions.cmake

To hold visit-defined functions (not needed by pluginVsInstall, which are store in VisItMacros.cmake).
Consolidated logic for setting VISIT_3RDPARTY_VAR's.

* Create VisItOptions.cmake to hold VisIt's configuration options.

Fix error with inclusion of VisItParallel.cmake.
Remove debugging messages from VISIT_3RDPARTY_VAR function.

* Update modifications comment.

* Add status message regarding parallel verison of VisIt.

Co-authored-by: Mark (he/his) C. Miller <miller86@llnl.gov>

Co-authored-by: Mark (he/his) C. Miller <miller86@llnl.gov></small>

<a href='https://github.com/visit-dav/visit/commit/88b3c39bab528c1912f86c01433f7160a001a0c4' target='_blank'>View Commit</a>