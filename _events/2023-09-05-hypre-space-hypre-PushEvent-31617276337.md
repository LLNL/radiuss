---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/50467563?"
user: victorapm
date: 2023-09-05
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/commit/cd8f9c363e4839a952297280cef09cd5bf92b167
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/victorapm' target='_blank'>victorapm</a> pushed to <a href='https://github.com/hypre-space/hypre' target='_blank'>hypre-space/hypre</a>

<small>Keep smooth_num_levels in sync with amg_data (#954)

This solves an out-of-bounds memory error during `hypre_BoomerAMGSetup` when called multiple times without a call to `hypre_BoomerAMGDestroy` interleaved. This pull request makes sure that `smooth_num_levels` is reset to `hypre_ParAMGDataSmoothNumLevels(amg_data)` before the smoothers variable is allocated.</small>

<a href='https://github.com/hypre-space/hypre/commit/cd8f9c363e4839a952297280cef09cd5bf92b167' target='_blank'>View Commit</a>