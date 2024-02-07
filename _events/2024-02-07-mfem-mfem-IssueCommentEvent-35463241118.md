---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/90462987?"
user: M8kmyday
date: 2024-02-07
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4083
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/M8kmyday' target='_blank'>M8kmyday</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4083' target='_blank'>mfem/mfem#4083</a>.

<small>Yes, I want the 2D solver to follow the 3D partitioning.  I have to maintain the distribution of the mesh between the 2D and 3D solvers.  Otherwise, the DOFs get re-ordered, and I cannot import the 2D solution into the 3D solution.  If I use the serial mesh output, then the 2D solver will partition the mesh differently than the way the 3D solver did it, and the DOF orderings between the 2D and 3D solvers will be different.  When I use ParPrint, then the imported mesh in the 2D solver distributes the same as the 3D solver, the DOF orderings remain the same, and my solution exported from the 2D solver reads into the 3D solver with the correct DOF order....</small>

<a href='https://github.com/mfem/mfem/issues/4083' target='_blank'>View Comment</a>