---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/96548734?"
user: JeremiahDBrown
date: 2022-10-26
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3156
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/JeremiahDBrown' target='_blank'>JeremiahDBrown</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3156' target='_blank'>mfem/mfem#3156</a>.

<small>For the time being, I've implemented this as outlined above.  $\psi$ is a grid function, and I've created a ConvolutionCoefficient derived from VectorCoefficient.  The Eval method uses the GetVectorVal method to obtain values of $\psi$ and $e$ to compute the value to be projected.  Every time step, I tell the coefficient to make a backup copy of $\psi$, as once I call ProjectCoefficient, the results of psi->GetVectorValue are no longer valid....</small>

<a href='https://github.com/mfem/mfem/issues/3156' target='_blank'>View Comment</a>