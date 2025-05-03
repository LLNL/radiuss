---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/43390106?"
user: sbugenha
date: 2025-05-02
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/531
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sbugenha' target='_blank'>sbugenha</a> commented on issue <a href='https://github.com/mfem/mfem/issues/531' target='_blank'>mfem/mfem#531</a>.

<small>@v-dobrev, thanks for the tip. Yes, I was calling BilinearForm::ComputeElementMatrices in the constructor for a custom NLF integrator that also uses some element matrices from BilinearForm operators. I got rid of that line of code and instead looped through the elements and saved the element matrices into arrays in the constructor. The code works now - thanks for your help!...</small>

<a href='https://github.com/mfem/mfem/issues/531' target='_blank'>View Comment</a>