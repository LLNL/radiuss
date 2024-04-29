---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/148477105?"
user: FH-9
date: 2024-04-28
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4269
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/FH-9' target='_blank'>FH-9</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4269' target='_blank'>mfem/mfem#4269</a>.

<small>I realized the integral computation was way off. I think after projecting the gradient degrees of freedom back onto the finite dimensional space of the solution, the integral, $\int \left( \frac{d}{dx} \tilde{p} \right)^2 dx \approx \int \left(\sum_k \hat{dp}_k \phi_k \right)^2 dx$, can be cast into the the quadratic form $\hat{x}^T M \hat{x}$, where $\hat{x}^T$ is the vector of gradient degrees of freedom, and $M$ is the extrapolated mass integrator (since the integral is over the target element only). I have updated the code but I am it is still blowing up. Is my reasoning here correct? And do you notice anything wrong with the code? ...</small>

<a href='https://github.com/mfem/mfem/issues/4269' target='_blank'>View Comment</a>