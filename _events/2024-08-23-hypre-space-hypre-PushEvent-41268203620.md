---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/50467563?"
user: victorapm
date: 2024-08-23
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/commit/3caa81955eb8d1b4e35d9b450e27cf6d07b50f6e
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/victorapm' target='_blank'>victorapm</a> pushed to <a href='https://github.com/hypre-space/hypre' target='_blank'>hypre-space/hypre</a>

<small>Add memory usage monitoring functions (#1112)

Add host and device memory monitoring capabilities. 

* Move umpire functions to memory.c
* Add hypre_HostMemoryGetUsage for retrieving CPU RAM stats (VmSize, VmPeak, VmRSS, VmHWM)
* Add hypre_UmpireMemoryGetUsage for retrieving GPU RAM stats via umpire (DevSize, DevPeak, ...)
* Add declaration for HYPRE_MemoryPrintUsage
* Annotate a few functions with hypre_MemoryPrintUsage
* Add hypre/HYPRE_SetLogLevel and documentation
* Add log level option to IJ driver
* Apply astyle</small>

<a href='https://github.com/hypre-space/hypre/commit/3caa81955eb8d1b4e35d9b450e27cf6d07b50f6e' target='_blank'>View Commit</a>