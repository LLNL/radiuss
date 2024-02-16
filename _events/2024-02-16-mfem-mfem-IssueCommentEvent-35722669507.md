---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-02-16
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/303
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/pull/303' target='_blank'>mfem/mfem#303</a>.

<small>Hello here, by matter of coincidence, I am starting work on some code also based on this formulation of HDG 🤩 . It looks like a great amount of work done here! 😮 However, I would like to take a different approach to this and design the interface very differently. Basically, I would let users to construct a classical mixed formulation with continuous fluxes and discontinuous potentials with some helper wrapper for these Darcy-like systems. The user would have then an option to enable hybridization in a similar fashion to `BilinearForm::EnableHybridization()`, so just a single line of code giving the ability to transform the system to HDG or skip hybridization all together, which might make sense for low orders. It would also spare the code and user in the end of a lot of specifics and in particular some of the new massive XFESXElement integrators, which I do not like much personally 😕 . I think I will open a separate branch for that, but do not get me wrong, I would like to (re)use and some of the code base from here, which you have spent some sleepless nights on 😳, I guess, and is of a great value 👍 . Maybe we should just discuss how structure and pack the whole thing and present it to the user 🤔 😉 ....</small>

<a href='https://github.com/mfem/mfem/pull/303' target='_blank'>View Comment</a>