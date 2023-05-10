---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6224451?"
user: cnpetra
date: 2023-05-09
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3639
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/cnpetra' target='_blank'>cnpetra</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3639' target='_blank'>mfem/mfem#3639</a>.

<small>Moving limits/bounds are not supported by HiOp. There are algorithmic considerations why this is not supported. One way is do this is, as you alluded to, to continually restart the solver and move the density bounds as you find it necessary. I would let the optimizer take 5-6 iterations between restarts to build enough secant memory used to approximate the Hessian. ...</small>

<a href='https://github.com/mfem/mfem/issues/3639' target='_blank'>View Comment</a>