---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4259064?"
user: najlkin
date: 2025-04-25
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4829
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/najlkin' target='_blank'>najlkin</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4829' target='_blank'>mfem/mfem#4829</a>.

<small>I can confirm the latest patch fixes the problem 🎉 . However, let me bring up again that conceptually the main problem is not that some case is not supported by `QuadratureInterpolator`, which is understandable, but that there is no fallback in `QuadratureFunction::ProjectGridFunction()`, so even things that worked in version 1.* do not work anymore and sometimes are not even detected....</small>

<a href='https://github.com/mfem/mfem/issues/4829' target='_blank'>View Comment</a>