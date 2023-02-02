---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2023-02-02
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/ad0c1efa9149023f1f8e1ef5fa6164fe47414096
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Consolidate logic related to config-site files.

Windows config-site now included at same location in CMakeLists.txt as other platforms.
Use full-path (via CMAKE_CURRENT_SOURCE_DIR) when setting VISIT_CONFIG_SITE_FILE for easier testing of existence.
Modified windows config-site file to use CMAKE_CURRENT_SOURCE_DIR instead of VISIT_SOURCE_DIR which hasn't been set when the file is included.
Remove MSVC version test, it is handled in CheckMinimumCompilerVersion.</small>

<a href='https://github.com/visit-dav/visit/commit/ad0c1efa9149023f1f8e1ef5fa6164fe47414096' target='_blank'>View Commit</a>