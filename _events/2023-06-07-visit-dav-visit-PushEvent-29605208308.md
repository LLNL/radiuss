---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2023-06-07
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/03fec2f93fbbd146f7f3d28c1ece5d8646da232b
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Add qt6 support (#18697)

* Add support for Qt 6.

* Misc Qt6 fixes.

* Add qt6 support to build_visit.
Force VTK9 when building QT6.
Update qwt version for qt6.

* Change when config-site is included for Windows.

Move it to after the 'project' call so that compiler information is known.
This allows support of multiple versions of MSVC for pre-built TP libs, where perhaps the TP versions are different depending on compiler.
Made the inclusion of the config-site a macro to reduce code duplication.

* Change FindTiff.cmake so FindVTK9 doesn't complain.

* Add MSVC2022 support to windows-config.

In support of Qt 6 port.

* Add support for Qt 6.

* Misc Qt6 fixes.

* Change when config-site is included for Windows.

Move it to after the 'project' call so that compiler information is known.
This allows support of multiple versions of MSVC for pre-built TP libs, where perhaps the TP versions are different depending on compiler.
Made the inclusion of the config-site a macro to reduce code duplication.

* Change FindTiff.cmake so FindVTK9 doesn't complain.

* Add MSVC2022 support to windows-config.

In support of Qt 6 port.

* Add qt6 support to build_visit.
Force VTK9 when building QT6.
Update qwt version for qt6.

* Fix CMAKE location for bv_qt6.
Ensures Qt6 can build where system cmake doesn't exist.

* More build_visit updates for QT6

set DO_QT to "no" if DO_QT6 is enabled.
Fix libvtklibxml2 location (lib64 vs lib) when building VTK9.

* Update release notes with Qt 6 support.
Remove notation from 3.3.4 and put in 3.4.0.

* Use idClicked instead of buttonClicked for QButtonGroup with Qt6.

* Update FindQt5.cmake

Put in missing OPENGL_LIBRARIES for QT_QTGUI_LIBRARY.

* Add Qt 6 support to poodle18.cmake.
Enabled by setting CMake var USE_QT6 to ON.
Fix comments and opengl issues with FindQt modules.

* Reconsolidate QT find modules into one supporting both version 5 and 6.

* Add comments per reviewer request.

* Update relnotes3.4.0.html

Remove extraneous line.

* Disable embree, ispc, tbb when building VTK 9.
Ospray 2.8 (used by vtk9) bundles these so separate builds aren't necessary.

* Disable pyside when building Qt 6.
Temporary measure until build module for pyside 6 can be implemented.

* Disable Qt(5) when building Qt 6.

* Add cfitsio 4.2.0 when building with MSVC2022.

* Update minimum compiler version checks for g++.

If building qt6, minimum g++ version is 8.1.

* Update build_visit docs for QT6.

Add links to Qt's Qt6 linux requirments.

Add section to Basic Usage, related to minimum compiler versions.

* Add comments regarding change from 'updateGL' to 'update' calls in ClipEditor files.

Qt 6 no longer has an 'updateGL' method, and the 'update' method seems to do the job.

* fix spacing in bullet list.

* Fix qt6 build failure when symlinks present in build dir.

* Fix host profile issues when using --qt6.

* Fix typo in Qt 6 version var.</small>

<a href='https://github.com/visit-dav/visit/commit/03fec2f93fbbd146f7f3d28c1ece5d8646da232b' target='_blank'>View Commit</a>