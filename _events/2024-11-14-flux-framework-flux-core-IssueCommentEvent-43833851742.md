---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-11-14
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6437
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6437' target='_blank'>flux-framework/flux-core#6437</a>.

<small>@wadudmiah I don't see that you tried an srun command targeted at two nodes after you launched the allocation - I just see you trying an ssh command, and flux start in absence of a launching or bootstrap mechanism. Please do salloc with two nodes, and then an srun that also targets two nodes and runs flux start. The example that I provided (simplified):...</small>

<a href='https://github.com/flux-framework/flux-core/issues/6437' target='_blank'>View Comment</a>