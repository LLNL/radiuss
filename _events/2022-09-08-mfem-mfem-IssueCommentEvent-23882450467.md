---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/53028846?"
user: logantm2
date: 2022-09-08
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3193
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/logantm2' target='_blank'>logantm2</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3193' target='_blank'>mfem/mfem#3193</a>.

<small>> Yes, I think you're right, `ParMesh` will only create boundary elements that correspond to faces that each partition "owns", so some of the duplicated boundary elements will disappear during the partitioning. You might need to do some of the book-keeping yourself using the shared face (/face neighbor) information....</small>

<a href='https://github.com/mfem/mfem/issues/3193' target='_blank'>View Comment</a>