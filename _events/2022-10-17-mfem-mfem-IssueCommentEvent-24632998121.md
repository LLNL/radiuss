---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2022-10-17
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3166
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3166' target='_blank'>mfem/mfem#3166</a>.

<small>I seems like there is some misunderstanding here: `dofs` is both input and output parameter here and its size should remain the same. We are simply converting "scalar" dofs to "vector" dofs for a given vector component `vd` (typically, `0 <= vd < vdim`.)...</small>

<a href='https://github.com/mfem/mfem/issues/3166' target='_blank'>View Comment</a>