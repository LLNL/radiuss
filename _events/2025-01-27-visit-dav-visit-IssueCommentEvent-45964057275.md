---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2025-01-27
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/20201
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/20201' target='_blank'>visit-dav/visit#20201</a>.

<small>@nDimensionalSpace I think we're just dealing with a *corner case* here. I mean, we don't often deal with meshes consisting of a single point. There is nothing inherently invalid about that but we do have a sense of *spatial extents* that comes into play in, for example, establishing the field of view. And, if the mesh has a single point, then its spatial extents are effectively zero. I am not sure the rest of VisIt will play nice with that..even if you have some way to try to *force* VisIt to use specific values for spatial extents. So, I think that is problem 1. And, I think that is then preventing it from rendering the vector field (in this case a single vector glyph), in such a way that it is visible....</small>

<a href='https://github.com/visit-dav/visit/issues/20201' target='_blank'>View Comment</a>