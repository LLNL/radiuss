---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2022-12-14
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3365
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3365' target='_blank'>mfem/mfem#3365</a>.

<small>`ALGOIM_REQUIRED_PACKAGES` should be spelled as `Algoim_REQUIRED_PACKAGES` and the contents should be `"Blitz"`, not `"BLITZ"`. This is because of the naming of the files `FindAlgoim.cmake` and `FindBlitz.cmake` and the way they call `mfem_find_package` -- the first argument is `Algoim`/`Blitz` (this should be consistent with the filename, `Find*.cmake`). The second argument (`ALGOIM`/`BLITZ`, respectively) determines the names of the output variables: like `ALGOIM_FOUND`, `ALGOIM_INCLUDE_DIRS`, `ALGOIM_LIBRARIES`, etc....</small>

<a href='https://github.com/mfem/mfem/issues/3365' target='_blank'>View Comment</a>