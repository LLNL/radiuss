---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/100882624?"
user: Raj-Bagri1
date: 2022-10-25
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4718
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/Raj-Bagri1' target='_blank'>Raj-Bagri1</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/4718' target='_blank'>flux-framework/flux-core#4718</a>.

<p>Update flux drain reason without undraining first</p><small>At the moment, it seems as though you have to undrain the node and then drain it out again to change the listed reason as to why the node is drained. So, for example, when a node fails nodediag during eplilog, the node will drain itself out with a reason such as `nodediag failed amdgpu`. If we then want to change this reason to add a servicenow incident number to show that the issue is being addressed or to change the reason to a more apt reason in such cases as the bus the gpu is running on is bad, we need to currently undrain the node and then re-drain it with the proper wording....</small><a href='https://github.com/flux-framework/flux-core/issues/4718' target='_blank'>View Comment</a>