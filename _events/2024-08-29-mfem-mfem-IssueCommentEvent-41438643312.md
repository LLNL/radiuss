---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2024-08-29
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4416
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4416' target='_blank'>mfem/mfem#4416</a>.

<small>Great, if you can reproduce that it will be much easier, I cannot, all tests pass for me. Probably because I use METIS 5. @j-signorelli , I agree with you that it might not be related to this PR, but implementation `GetEssentialVDofs()` is very simple. Nothing else than what you would do by hand, i.e., iteration over boundary elements and marking dofs if the attribute matches. Unless the mesh is non-conforming, have you checked that? (by `Nonconforming()`). Otherwise it is a bit of mystery 🤔 ...</small>

<a href='https://github.com/mfem/mfem/pull/4416' target='_blank'>View Comment</a>