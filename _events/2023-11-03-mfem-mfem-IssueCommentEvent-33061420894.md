---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-11-03
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3611
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3611' target='_blank'>mfem/mfem#3611</a>.

<small>The reason for the worse errors with uniform refined NC tet meshes is that (if I remember correctly) in the NC refinement algorithm the choice of which octahedron diagonal to use for the tet refinement is fixed. In general, this can lead to refinements with degenerating quality (both for local and uniform NC tet AMR), so it is probably a good idea to consider fixing this drawback....</small>

<a href='https://github.com/mfem/mfem/pull/3611' target='_blank'>View Comment</a>