---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/60271325?"
user: Heinrich-BR
date: 2024-07-17
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4387
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/Heinrich-BR' target='_blank'>Heinrich-BR</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4387' target='_blank'>mfem/mfem#4387</a>.

<small>Yes, indeed. In the extracted submesh, boundary attribute 3 is the only one that is being inherited as you would expect (it's the upper half of boundary attribute 3 on the original mesh). I believe this is because it's the last boundary attribute to be set, so that it overrides the others, as opposed to being added to them....</small>

<a href='https://github.com/mfem/mfem/issues/4387' target='_blank'>View Comment</a>