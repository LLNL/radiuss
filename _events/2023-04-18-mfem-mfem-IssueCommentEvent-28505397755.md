---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-04-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3600
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3600' target='_blank'>mfem/mfem#3600</a>.

<small>Looking at the errors, they seem to be only in places where the function call does not use the fully qualified `std::pow` but just the short version, `pow`. Can't you just add the `std::` prefix to fix this?...</small>

<a href='https://github.com/mfem/mfem/pull/3600' target='_blank'>View Comment</a>