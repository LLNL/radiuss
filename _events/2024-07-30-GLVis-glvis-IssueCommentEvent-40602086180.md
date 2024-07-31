---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2024-07-30
repo_name: GLVis/glvis
html_url: https://github.com/GLVis/glvis/issues/283
repo_url: https://github.com/GLVis/glvis
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/GLVis/glvis/issues/283' target='_blank'>GLVis/glvis#283</a>.

<small>Changing to using apple clang isn't a particularly practical workflow, as I end up needing 3 builds of mfem locally (one inside of Palace, one for development of mfem patches, and then one for glvis). I have instead opted for reading the apple error backtraces when glvis crashes, and then calling the failing mfem methods directly to debug them, which has been fruitful. The separate builds can be particularly troublesome if I have to edit things within mfem in order to fix the glvis interaction, as that means developing with apple clang becomes necessary rather than llvm which is needed for all my other building....</small>

<a href='https://github.com/GLVis/glvis/issues/283' target='_blank'>View Comment</a>