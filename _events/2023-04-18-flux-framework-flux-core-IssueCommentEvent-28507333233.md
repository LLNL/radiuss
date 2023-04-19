---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2023-04-18
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5079
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5079' target='_blank'>flux-framework/flux-core#5079</a>.

<small>Yeah, the MPI tests seem to be brittle in the conda-forge build environment. Since Flux does not require MPI to build (it only requires it run some MPI launch testing), my inclination would be to build the conda-forge flux-core package _without_ all the MPI permutations, and then separately test that Flux can launch the various MPIs packaged in conda....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5079' target='_blank'>View Comment</a>