---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1349371?"
user: jakubcerveny
date: 2022-10-31
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3247
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/jakubcerveny' target='_blank'>jakubcerveny</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3247' target='_blank'>mfem/mfem#3247</a>.

<small>Hi @mlstowell, I think you are right. It didn't occur to me before but we've actually never included the attributes in the rebalancing messages, because it was assumed they are the same as the attributes of the respective root elements. I'm not ever sure now if it is conceptually correct that the attributes of refined elements differ from their parents. If we're OK with that (i.e. there are no side effects elsewhere) we could add support for rebalancing with user-defined attributes. Another approach to store the material indicator data is using a piecewise-constant (L2) ParGridFunction where post-rebalancing Update() is supported....</small>

<a href='https://github.com/mfem/mfem/issues/3247' target='_blank'>View Comment</a>