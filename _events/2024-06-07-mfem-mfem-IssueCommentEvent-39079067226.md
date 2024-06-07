---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-06-07
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4346
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4346' target='_blank'>mfem/mfem#4346</a>.

<small>I think @jandrej is right -- all your source files that use `mfem::forall` need to be marked as CUDA sources when `MFEM_USE_CUDA` is true. This can be done with something like this: https://github.com/mfem/mfem/blob/c3eb769a2a316a68fd9a00448e20ca7cff4c8b7c/config/cmake/modules/MfemCmakeUtilities.cmake#L87-L90...</small>

<a href='https://github.com/mfem/mfem/issues/4346' target='_blank'>View Comment</a>