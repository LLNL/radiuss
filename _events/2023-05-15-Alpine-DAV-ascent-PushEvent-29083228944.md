---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1194526?"
user: cyrush
date: 2023-05-15
repo_name: Alpine-DAV/ascent
html_url: https://github.com/Alpine-DAV/ascent/commit/78783ff8d0f0ab4f313625efaa6cbe656d62818a
repo_url: https://github.com/Alpine-DAV/ascent
---

<a href='https://github.com/cyrush' target='_blank'>cyrush</a> pushed to <a href='https://github.com/Alpine-DAV/ascent' target='_blank'>Alpine-DAV/ascent</a>

<small>update Ascent to use VTKm 2.0 (#1118)

* update to vtkm 2.0 first pass

* start of replacing compvec. need vtkm 2.0 changes

* rewrote PointMerge. CompVEc not working yet.

* clean up ParticleMerging

* falsly assuming addDomain overwrites already present domain. Now output is correct

* revert compvec and fix cmakelists

* use vtkm's arrayhandlestride for type checking to ignore the storage tags:

* begin vtk-m 2.0 tpl build update changes

* vtkm overwrites filter's active field, need to tell input

* refactor vtkm field to bp conversion to defend against non zero copy cases

* fix read the docs due to env change

* update fides pkg

* update ci containers to new vtkm

* adj build ascent tests

* use new vtkm api for babel flow filter

* type swtich yard logic fixes and avoid wrapping coords as field

* always show cmake version

* update uberenv

* fix mention of apple-clang

* new and improved vector switch yard

* about updates

* use vtk-m config.mk

---------

Co-authored-by: Nicole Marsaglia <marsagli@uoreogn.edu>
Co-authored-by: Cyrus Harrison <cyrush@llnl.gov></small>

<a href='https://github.com/Alpine-DAV/ascent/commit/78783ff8d0f0ab4f313625efaa6cbe656d62818a' target='_blank'>View Commit</a>