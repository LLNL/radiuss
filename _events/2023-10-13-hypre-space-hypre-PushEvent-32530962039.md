---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/50467563?"
user: victorapm
date: 2023-10-13
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/commit/8ff65e81245aecde654854a85fdf1df8ed12db75
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/victorapm' target='_blank'>victorapm</a> pushed to <a href='https://github.com/hypre-space/hypre' target='_blank'>hypre-space/hypre</a>

<small>Improve MGR data printing (#976)

This enhances what print_level can achieve in MGR. Particularly, now we can dump linear system info to files according to the print_level code. We also have the ability now of printing a sequence of linear systems to file (useful when hypre is used in time-stepping application).

A detailed list of changes is given below:

* Add utilities for creating/checking directories
* Add print_level codes to MGR and new info_path member
* Add hypre_MGRDataPrint
* Add call to hypre_MGRDataPrint and logic to update the print_level variable
* Update MGRSolve with new print_level logic
* Remove hypre_MGRWriteSolverParams
* Update documentation for HYPRE_MGRSetPrintLevel
* Implement new logic for HYPRE_MGR_PRINT_MODE_ASCII</small>

<a href='https://github.com/hypre-space/hypre/commit/8ff65e81245aecde654854a85fdf1df8ed12db75' target='_blank'>View Commit</a>