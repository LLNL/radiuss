---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-05-25
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/2666
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/issues/2666' target='_blank'>mfem/mfem#2666</a>.

<small>1. This might be the case, but I would be pretty skeptical until some high granularity profiling data is available. Moving around in NCMesh though, there is an enormous scope for using the stl rather then home rolled algorithms. For instance, most of the Table structures could be easily handled by an unordered_map, for which we can design perfect hashes given we know so much information about the keys a priori. Right now I am focused on correctness rather than performance however, so I have only changed these over in cases where it improves readability, leaving the serious refactors for once I have feature completeness....</small>

<a href='https://github.com/mfem/mfem/issues/2666' target='_blank'>View Comment</a>