---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-02-01
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4106
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4106' target='_blank'>mfem/mfem#4106</a>.

<small>Yes, we have not really considered thread safety in the `Memory` and `MemoryManager` classes -- basically allocation are never done inside `mfem::forall*` calls, so none of the MFEM backends need it....</small>

<a href='https://github.com/mfem/mfem/issues/4106' target='_blank'>View Comment</a>