---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-02-02
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4102
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4102' target='_blank'>mfem/mfem#4102</a>.

<small>Since `aux1` is internal, I'm not sure we really need to ensure its monolithic Vector is in sync with its sub-vectors. For example, if we only use its sub-vectors to perform operations, then sync with the monolithic vector is probably not necessary. Do we actually use the monolithic version of `aux1` anywhere? ...</small>

<a href='https://github.com/mfem/mfem/issues/4102' target='_blank'>View Comment</a>