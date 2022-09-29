---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1278247?"
user: tzanio
date: 2022-09-28
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3235
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/tzanio' target='_blank'>tzanio</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3235' target='_blank'>mfem/mfem#3235</a>.

<small>> May I chime in here? 😄 . In my opinion, the linear and bilinear form assembly are two very different concepts. One involves the actual assembly level (matrix-free, partial, full) the other one is about the algorithm of the assembly procedure., i.e., it's always full assembly but with traditional or sum factorization. So, to that end, I don't think there should be an assembly level enum in linear forms, but rather a single false/true flag to enable sum factorization or not. So basically as it was before. I believe assembly level in linear forms can introduce more confusion to the users. I also think that we don't have to have the two cases (linear and bilinear forms) linked, meaning we don't need to enable or disable both at the same time. Enabling sum factorization for linear forms changes nothing to the linear system, but enabling matrix-free/ PA assembly levels actually changes the form of the linear systems., i.e, the need to use other solvers/preconditioners, etc. So I agree with eventually finding a way to have the sum factorization as default for the linear forms, but still, it should be independent of the bilinear form assembly level....</small>

<a href='https://github.com/mfem/mfem/pull/3235' target='_blank'>View Comment</a>