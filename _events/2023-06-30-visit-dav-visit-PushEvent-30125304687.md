---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2023-06-30
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/9b539cb4fa0e6af2cae48de039f1d1aa0bc7f0a1
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Fix spatial extents retrieval for vtkPolyData with VTK-9. (#18811)

Previous behavior of 'GetBounds' call on poly data was to return the extents of the cells, new behavior is to return the extents of the point set, which may not be fully connected to cells.
To preserve previous behavior, call GetCellsBounds with vtk 9.

This showed up in the  reflect operator test, where Boundary plot of Globe was projected and reflected.

Also removed an unnecessary call to GetBounds in the Neighbor expression because the results were never used.</small>

<a href='https://github.com/visit-dav/visit/commit/9b539cb4fa0e6af2cae48de039f1d1aa0bc7f0a1' target='_blank'>View Commit</a>