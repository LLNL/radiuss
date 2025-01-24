---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2025-01-22
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/commit/7c540be32e2c89b568215c25f4e1fd497ec617a1
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> pushed to <a href='https://github.com/LLNL/sundials' target='_blank'>LLNL/sundials</a>

<small>Reorganized organization of checkNvector routines (#647)

Clean up how ARKODE and its steppers check for required and optional
N_Vector routines. 

1. Stepper-specific N_Vector operation checks have been removed.
2. ARKODE performs an initial check on the supplied N_Vector for
operations that are always required.
3. Individual ARKODE utilities perform their own N_Vector checks when
they are configured.
4. ARKODE then performs a final check after user configuration is
complete to check any remaining N_Vector operation requirements.

---------

Co-authored-by: David Gardner <gardner48@llnl.gov></small>

<a href='https://github.com/LLNL/sundials/commit/7c540be32e2c89b568215c25f4e1fd497ec617a1' target='_blank'>View Commit</a>