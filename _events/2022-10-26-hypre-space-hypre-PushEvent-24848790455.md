---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/30503782?"
user: osborn9
date: 2022-10-26
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/commit/247c168ee7724a3a741db70af7f68fddd3a1718c
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/osborn9' target='_blank'>osborn9</a> pushed to <a href='https://github.com/hypre-space/hypre' target='_blank'>hypre-space/hypre</a>

<small>bugfix/tsuji1/dsuperlu to update FEI interface (#748)

* Fixing the FEI interface to SuperLU_Dist. This uses the same structs
as src/parcsr_ls/dsuperlu.c.

* Updates to the CMake build system and other spots to support SuperLU_Dist, SuperLU, and the FEI.
Some Windows build bits.

* Reverting this change, it's just in the comments.

* Changes from Tim Dunn's FEI branch (feature/dunn13/tad220914-fei).
This prevents the solver from exiting out with a failure even though
the initial guess is the solution. There is also a fix to prevent a
floating point exception.

* Removing this #ifndef, as it is no longer necessary for our Windows build.

* Only enable CXX if building the FEI.</small>

<a href='https://github.com/hypre-space/hypre/commit/247c168ee7724a3a741db70af7f68fddd3a1718c' target='_blank'>View Commit</a>