---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2025-01-21
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4649
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4649' target='_blank'>mfem/mfem#4649</a>.

<small>> quadinterpolator_face.cpp:467-468 Should this check be removed? It looks like this always evaluates to true, but is intended to fail if `eval_flags` requests derivatives. mesh.cpp:14399 sets derivatives as being required for face jacobians, so I changing this to correctly exclude derivatives causes an unintended assertion failure....</small>

<a href='https://github.com/mfem/mfem/pull/4649' target='_blank'>View Comment</a>