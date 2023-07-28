---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-07-27
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3794
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3794' target='_blank'>mfem/mfem#3794</a>.

<small>I'm not sure what you are doing exactly -- you are showing errors from a parallel FE space methods while before you were talking about a serial mesh. If you look at `Mesh::GenerateFaces()` (which is called by `FinalizeTopology`) you can see that the array `faces_info` is being re-generated based the element connectivity....</small>

<a href='https://github.com/mfem/mfem/issues/3794' target='_blank'>View Comment</a>