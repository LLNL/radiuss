---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2022-11-14
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/22cb0b2d16d0cdf41ccf17f2547d296f0a04b593
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Update CMake version to 3.24.2. (#18272)

* Update CMake version to 3.24.2.
Remove flags that turned off CMAKE_USE_OPENSSL. Resolves #17927.
Add openssl-devel to fedora31 dockerfile so that CMake will build there.

* Fix ci for new cmake.

* Add '--recursive' to git clone command.

* Fix ci cmake-configure error.

* Add CMakeUserPresets to .gitignore

Newer CMake has the concept of 'presets' that can be used to pre-fill cache items or setup a build. Global presets are stored in the root directory and are named 'CMakePresets.json'. User presets are also stored in the root directory and are named 'CMakeUserPresets.json'.  User presets shouldn't be added to repo and tracked, so I added them to .gitignore.</small>

<a href='https://github.com/visit-dav/visit/commit/22cb0b2d16d0cdf41ccf17f2547d296f0a04b593' target='_blank'>View Commit</a>