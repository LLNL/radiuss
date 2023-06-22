---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/137279059?"
user: GanboD
date: 2023-06-21
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/931
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/GanboD' target='_blank'>GanboD</a> open issue <a href='https://github.com/hypre-space/hypre/issues/931' target='_blank'>hypre-space/hypre#931</a>.

<p>Fortran style 1 indexing fails to converge for multi-gpu BoomerAMG</p><small>I have tested the GPU version by adapting the ex5f_cptr.f source code to import a linear system from my own application. The index of unknowns start from 1 rather than 0. The single GPU version works fine. But multi-GPU version fails to converge or even crash. No problem with CPU version. Multi-GPU version works fine as well if I change the index such that it start from 0. I believe that there is a bug in MPI communication in the GPU version when index start from 1. The MPI version used in my testing is the OpenMPI 3.1 version provided in the NVIDIA HPC SDK package. Hypre is configured with...</small><a href='https://github.com/hypre-space/hypre/issues/931' target='_blank'>View Comment</a>