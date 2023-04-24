---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/50467563?"
user: victorapm
date: 2023-04-23
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/pull/889
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/victorapm' target='_blank'>victorapm</a> commented on issue <a href='https://github.com/hypre-space/hypre/pull/889' target='_blank'>hypre-space/hypre#889</a>.

<small>Hi Pierre, thank you for trying this so quickly! It seems to me (please, correct me if I'm wrong) that `PetscFinalize` does not call `HYPRE_Finalize`, instead the PETSc user would need to explicitly call `PetscHYPREFinalizePackage` to finalize hypre as done in:...</small>

<a href='https://github.com/hypre-space/hypre/pull/889' target='_blank'>View Comment</a>