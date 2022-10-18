---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5539428?"
user: prj-
date: 2022-10-17
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/755
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/prj-' target='_blank'>prj-</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/755' target='_blank'>hypre-space/hypre#755</a>.

<small>Turns out this "bug" is also in `v2.16.0`, so we can't update to this release in PETSc (at least on the FreeBSD boxes). Rob, the following patch fixes things: https://github.com/prj-/hypre/commit/2eee2dbbccab02555282677c324d6e818832f3bb. It's applied on top of your `autoconf-update` branch, but it should apply to `master` as well. With the branch from my fork, PETSc pipeline is clean on FreeBSD (https://gitlab.com/petsc/petsc/-/pipelines/668363360), and this also fixes the present issue....</small>

<a href='https://github.com/hypre-space/hypre/issues/755' target='_blank'>View Comment</a>