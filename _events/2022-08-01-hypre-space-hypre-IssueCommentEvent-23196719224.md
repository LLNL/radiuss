---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/22554827?"
user: oseikuffuor1
date: 2022-08-01
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/705
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/oseikuffuor1' target='_blank'>oseikuffuor1</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/705' target='_blank'>hypre-space/hypre#705</a>.

<small>To add to Ulrike's comment, yes the main issue would be loss of accuracy due to roundoff error. When used as a preconditioner, this may be less of an issue however. The dynamic range issue would depend on the problem. AMG would encounter issues if the coarse problem is outside the dynamic range of the precision on the coarse level. There's not much you can do about that but to use a format with more precision, BFloats, or storing in higher precision while computing in lower precision, among other strategies....</small>

<a href='https://github.com/hypre-space/hypre/issues/705' target='_blank'>View Comment</a>