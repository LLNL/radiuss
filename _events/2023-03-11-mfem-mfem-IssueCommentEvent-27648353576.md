---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-03-11
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3531
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3531' target='_blank'>mfem/mfem#3531</a>.

<small>Another approach to help users detect this kind of issue at runtime is to add checks after calls of `Mult` that expect the result vector to not be re-located. The check will be to make sure the `Vector` was not re-located and trigger an error if that happened. Alternatively, instead of triggering an error, the implementation can just copy the data to the memory location where it was supposed to be....</small>

<a href='https://github.com/mfem/mfem/issues/3531' target='_blank'>View Comment</a>