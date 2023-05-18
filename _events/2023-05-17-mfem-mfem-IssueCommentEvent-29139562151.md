---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-05-17
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3671
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3671' target='_blank'>mfem/mfem#3671</a>.

<small>The issue appears to not actually be related to the quadratic mesh, but just to using a quadratic H1 space on prisms. Another mesh `p1_prism.msh` has been added to the branch, and running ex6p with that mesh causes an essentially identical failure. As with above, Rank 1 is left with local dof that need ghost dofs finalized before it can resolve, however those ghost dofs are owned by rank 1, so rank 0 and rank 2 have exited....</small>

<a href='https://github.com/mfem/mfem/issues/3671' target='_blank'>View Comment</a>