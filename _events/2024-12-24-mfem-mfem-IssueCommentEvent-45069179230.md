---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-12-24
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4642
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4642' target='_blank'>mfem/mfem#4642</a>.

<small>Just to add some more details: if you have a `ParGridFunction pgf` you can get a reference to the `GroupCommunicator` using `pgf.ParFESpace()->GroupComm()`. The `GroupCommunicator` can then be used to perform `Reduce` and `Bcast` operations just on the shared dofs of `pgf`. In your case, you can use `Reduce` with reduce operation `GroupCommunicator::Max`, as @vladotomov pointed out. The reduce operation puts the reduced value just on the master rank for that dof, so you need to call `Bcast` if you want that value distributed to all ranks in the shared dof group....</small>

<a href='https://github.com/mfem/mfem/issues/4642' target='_blank'>View Comment</a>