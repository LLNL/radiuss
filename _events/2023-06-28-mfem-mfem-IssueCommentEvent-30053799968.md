---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2023-06-28
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3081
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3081' target='_blank'>mfem/mfem#3081</a>.

<small>I think I’m still worried about trying to automatically determine which MPI initialization the user wants, though admittedly don't have a great solution. I definitely agree with providing the wrapper for `MPI_Init_thread` in the `Mpi` class, though we should expose the option for `MPI_THREAD_FUNNELED` which I think is used in most cases. Generally I’m concerned about committing that we can determine which MPI initialization the user wants in all cases, and feel it might lead to a bad user experience if we only commit to some cases or if we get it wrong....</small>

<a href='https://github.com/mfem/mfem/pull/3081' target='_blank'>View Comment</a>