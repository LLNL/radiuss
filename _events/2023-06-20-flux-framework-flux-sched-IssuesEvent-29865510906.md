---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/40672572?"
user: stefangary
date: 2023-06-20
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1036
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/stefangary' target='_blank'>stefangary</a> closed issue <a href='https://github.com/flux-framework/flux-sched/issues/1036' target='_blank'>flux-framework/flux-sched#1036</a>.

<p>flux-run is not available when installing with Spack on RHEL and gcc@12.2.0</p><small>I attempted the follow the [instructions to install Flux with Spack](https://flux-framework.readthedocs.io/en/latest/quickstart.html#spack) v19.0 on an RHEL7.9 system. After I complete this process using [this install script](https://github.com/parallelworks/parsl_mpi/blob/main/run_on_cluster/step_01a_install_with_Spack.sh) (summary below), I can `spack load flux-sched` and access what I understand to be `flux-core` tools (e.g. `flux-start` and `flux-exec`) but I cannot access higher level `flux-run` and `flux-alloc`. Also, `flux --help` only shows the docs available to `flux-core`, not the docs available to `flux-sched`. I've repeated these steps on a different RHEL8.6 system with the same result as well as using different OpenMPI versions....</small><a href='https://github.com/flux-framework/flux-sched/issues/1036' target='_blank'>View Comment</a>