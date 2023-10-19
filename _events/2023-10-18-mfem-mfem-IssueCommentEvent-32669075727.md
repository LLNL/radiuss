---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17843342?"
user: vladotomov
date: 2023-10-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3936
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/vladotomov' target='_blank'>vladotomov</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3936' target='_blank'>mfem/mfem#3936</a>.

<small>@eliasboegel it all looks doable, but I'm not sure if `FindPointsGSLIB` is thread-safe, @kmittal2 is the person to comment on that. It works in parallel, and `GetBdrElementTransformation` has a version that doesn't reuse a global variable:...</small>

<a href='https://github.com/mfem/mfem/issues/3936' target='_blank'>View Comment</a>