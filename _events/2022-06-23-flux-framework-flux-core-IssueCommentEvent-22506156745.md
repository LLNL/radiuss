---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-06-23
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/384
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/384' target='_blank'>flux-framework/flux-core#384</a>.

<small>> We're actually lucky here since we already spawn the job shell (or IMP) instead of the job tasks directly. Therefore, I think for jobs at least, we'll be able to do many of the fixups in the job shell (changing working directory for example). Then, as noted above, the job shell can use `fork(2)` so that child pre-exec setup can still happen (setting up process affinity is the only example of this currently I think)...</small>

<a href='https://github.com/flux-framework/flux-core/issues/384' target='_blank'>View Comment</a>