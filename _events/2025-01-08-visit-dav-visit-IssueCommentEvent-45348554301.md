---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17075318?"
user: biagas
date: 2025-01-08
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/20177
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/biagas' target='_blank'>biagas</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/20177' target='_blank'>visit-dav/visit#20177</a>.

<small>VisIt has a couple of filters (vtkUnstructuredGridRelevantPointsFilter and vtkPolyDataRelevantPointsFilter) that will remove points not associated with any cells. It is called by avtCondenseDatasetFilter and uses a heuristic (which can be bypassed) to determine whether or not to use the filters.  avtCondenseDatasetFilter is used by avtPlot during its "ReduceGeometry" function. The individual vtk filters are also used in various places where it is important to remove the unused points.  @cyrush is this what you were thinking of ?...</small>

<a href='https://github.com/visit-dav/visit/issues/20177' target='_blank'>View Comment</a>