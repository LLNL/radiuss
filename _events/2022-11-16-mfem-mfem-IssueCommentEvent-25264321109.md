---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2022-11-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3280
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3280' target='_blank'>mfem/mfem#3280</a>.

<small>@mariobendra, just one point to be careful about: when you modify `config/defaults.mk`, you need to re-configure MFEM (with `make config [additional options]`) in order for those changes to take effect. If you did not run `make distclean` and just ran `make` then the new settings from `defaults.mk` were not used. If you used `make parallel [options]` then that does MFEM re-configuration and the problem is something else....</small>

<a href='https://github.com/mfem/mfem/issues/3280' target='_blank'>View Comment</a>