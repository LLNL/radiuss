---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-12-02
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4565
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4565' target='_blank'>mfem/mfem#4565</a>.

<small>One issue that I see is that it seems like you are calling `ParFiniteElementSpace::Update` before the call to `ParFiniteElementSpace::GetTrueUpdateOperator` and this is not allowed -- this is the first note in the doxygen comments of `GetTrueUpdateOperator`....</small>

<a href='https://github.com/mfem/mfem/issues/4565' target='_blank'>View Comment</a>