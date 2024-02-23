---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-02-23
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4148
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4148' target='_blank'>mfem/mfem#4148</a>.

<small>This looks like memory corruption from somewhere else, not from `NewtonSolver`. Can you try building MFEM in debug mode (option `MFEM_DEBUG=YES`) and run your code? In debug mode, the library performs some additional checks which may catch the issue. If this build runs with the same error, try running the code under valgrind -- that can also help you find memory related issues....</small>

<a href='https://github.com/mfem/mfem/issues/4148' target='_blank'>View Comment</a>