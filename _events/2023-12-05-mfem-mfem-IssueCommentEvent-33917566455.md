---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/9196588?"
user: termi-official
date: 2023-12-05
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4007
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/termi-official' target='_blank'>termi-official</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4007' target='_blank'>mfem/mfem#4007</a>.

<small>I am actually not sure if this is technically a bug or some kind of underspecification issue. From what I understand here is that the returned index from `GetSharedFace` returns an index to the face set of the parallel NC mesh and that the gaps are due to the faces of the ghost elements (=ghost faces?). However,  `GetSharedFace` is user-facing and the doc string tells that it returns the _local face index_....</small>

<a href='https://github.com/mfem/mfem/issues/4007' target='_blank'>View Comment</a>