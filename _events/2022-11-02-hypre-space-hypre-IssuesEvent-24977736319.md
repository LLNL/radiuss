---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/1668392?"
user: sanguinariojoe
date: 2022-11-02
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/767
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/sanguinariojoe' target='_blank'>sanguinariojoe</a> open issue <a href='https://github.com/hypre-space/hypre/issues/767' target='_blank'>hypre-space/hypre#767</a>.

<p>Drop HYPRE_INSTALL_PREFIX</p><small>I really think you should drop this custom HYPRE_INSTALL_PREFIX option. First, I do not see any benefit on setting HYPRE_INSTALL_PREFIX instead of the standard CMAKE_INSTALL_PREFIX. Second, after the first call to CMake, HYPRE_INSTALL_PREFIX renders useless, but it is still there inviting the user to set it. That is a huge problem when using ccmake or any cmake GUI in general (in which you are inexorably calling CMake several times)...</small><a href='https://github.com/hypre-space/hypre/issues/767' target='_blank'>View Comment</a>