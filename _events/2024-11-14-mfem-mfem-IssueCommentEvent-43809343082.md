---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-11-14
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4590
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4590' target='_blank'>mfem/mfem#4590</a>.

<small>In your `make parallel ...` command, remove the definitions of the variables `HYPRE_INC`, `HYPRE_LIB`, `SUNDIALS_INC`, and `SUNDIALS_LIB` -- those are not necessary and actually break the build by overriding values for `HYPRE_LIB` and `SUNDIALS_LIB` set in `config/defaults.mk`....</small>

<a href='https://github.com/mfem/mfem/issues/4590' target='_blank'>View Comment</a>