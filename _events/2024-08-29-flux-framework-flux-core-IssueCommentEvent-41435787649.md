---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2024-08-29
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6055
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6055' target='_blank'>flux-framework/flux-core#6055</a>.

<small>This became an issue on rzadams today. A job was canceled while the administrative prolog was running, but after rabbit file systems had mounted and the `nnf-clientmount` daemon had stopped. The job was never given a `finish` event so the `job-manager.epilog` (which turns back on `nnf-clientmount`) never started. However, the `dws-epilog` action started, holding the job until the file systems were cleaned up. At that point the `job-manager.epilog` was needed to turn the `nnf-clientmount` daemon back on to unmount the file systems and release the `dws-epilog` action....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6055' target='_blank'>View Comment</a>