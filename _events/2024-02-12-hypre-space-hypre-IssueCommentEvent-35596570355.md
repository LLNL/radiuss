---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/9383588?"
user: MatthiasHeilManchester
date: 2024-02-12
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1063
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/MatthiasHeilManchester' target='_blank'>MatthiasHeilManchester</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1063' target='_blank'>hypre-space/hypre#1063</a>.

<small>...actually just for completeness, here's the corresponding output from the more dramatic case. With the old version of hypre, the Newton solver takes three steps, and for each solve the outer GMRES iteration converges in about 20 iterations. With the new version, GMRES bails out after 100 iterations and the final approximation to the solution is so poor that the Newton method fails to converge within 10 iterations, at which point the code bails completely. ...</small>

<a href='https://github.com/hypre-space/hypre/issues/1063' target='_blank'>View Comment</a>