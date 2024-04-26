---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2024-04-25
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4268
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4268' target='_blank'>mfem/mfem#4268</a>.

<small>Can you step through on a debugger to see what is going on? My suspicion, if I understand correctly that the 17 million dof case is run on a single MPI rank, is that there is a quadrature data array being allocated (for example, for the element Jacobians) which might be larger than 2B entries and you are overflowing on the index. This happens for 3D Jacobians when `NE * NQ * 9 > 2^31-1` and should show up if you walk through the execution in `gdb` or `lldb`. MFEM does not use 64-bit integers for objects local to an MPI rank so would be unaffected by building Hypre, etc. with 64-bit integer support and  this seems consistent with the observation that increasing the number of MPI ranks makes the error go away....</small>

<a href='https://github.com/mfem/mfem/issues/4268' target='_blank'>View Comment</a>