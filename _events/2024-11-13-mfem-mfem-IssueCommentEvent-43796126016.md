---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-11-13
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4545
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>mfem/mfem#4545</a>.

<small>Cool, @mdavids-cfs , there is a big difference between the poor Gauss-Seidel and a multi-grid (BoomerAMG), as the residuum shows, but both did not converge. It is good for regression using plain `DarcyForm`, so we know it works the same way as `master`. However, the main benefit is that you may use turn on hybridization (`-hb`, works for RTs or DGs) or reduction of the DG flux (`-rd`) 😮 (I just added that reduction to `ex5-hdg.cpp`). Does that work?...</small>

<a href='https://github.com/mfem/mfem/issues/4545' target='_blank'>View Comment</a>