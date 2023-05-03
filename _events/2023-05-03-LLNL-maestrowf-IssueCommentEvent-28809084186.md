---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2023-05-03
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/issues/417
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> commented on issue <a href='https://github.com/LLNL/maestrowf/issues/417' target='_blank'>LLNL/maestrowf#417</a>.

<small>Ok, @aowen87 , I finally made some headway here.   Part of the problem appears to be pgen calling mpi ends up setting a bunch of mpi related env vars which confuses the batch job in an unintuitive way: the default slurm configuration is to treat missing `--export=[opts]` in the slurm batch headers to be set to ALL, which exports all env vars in the current environment when calling srun.  This is why you don't have to specify using your virtualenvironment python that maestro is installed into in your job steps.  However it also lets some MPI set things go though.  I was able to get a version with mpi in pgen and the job step to work just fine by hardwiring the `--export=NONE` option in maestro.   So a potential solution here is maybe adding some hooks in the spec somewhere to control this option and a few more potential options for controlling it:...</small>

<a href='https://github.com/LLNL/maestrowf/issues/417' target='_blank'>View Comment</a>