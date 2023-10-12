---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/11493037?"
user: pazner
date: 2023-10-11
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3927
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/pazner' target='_blank'>pazner</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3927' target='_blank'>mfem/mfem#3927</a>.

<small>The issue with your mesh is the use of 2147483647 as an element attribute number. In MFEM, there are arrays whose lengths scale with the maximum value of all attributes. This attribute number in your mesh probably comes from the Pointwise converter, see #3687....</small>

<a href='https://github.com/mfem/mfem/issues/3927' target='_blank'>View Comment</a>