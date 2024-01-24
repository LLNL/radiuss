---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/50467563?"
user: victorapm
date: 2024-01-24
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/commit/d36440c2e929875befedfdbf7942f0be8a95b0b0
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/victorapm' target='_blank'>victorapm</a> pushed to <a href='https://github.com/hypre-space/hypre' target='_blank'>hypre-space/hypre</a>

<small>Add iterative ILU0 (#1011)

This PR adds an interface to the iterative ILU algorithm with zero fill-in implemented in rocSPARSE.

The method is iterative in the context of the factorization phase. It works only in device runs (AMD). It can be used as preconditioner or complex smoother to BoomerAMG. Detailed list of changes:

* Add hypre_ILUSetupIterativeILU0Device
* Add Iterative ILU options to ILU's data structure
* Make use of iterative ILU options in IJ driver
* Add iterative ILU statistics
* Add BoomerAMG interface for using the new iterative ILU as complex smoother
* Turn on residuals when asking for conv. history</small>

<a href='https://github.com/hypre-space/hypre/commit/d36440c2e929875befedfdbf7942f0be8a95b0b0' target='_blank'>View Commit</a>