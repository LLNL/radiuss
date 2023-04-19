---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6109571?"
user: mlstowell
date: 2023-04-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3541
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/mlstowell' target='_blank'>mlstowell</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3541' target='_blank'>mfem/mfem#3541</a>.

<small>Regarding the use of `auto`, I don't think the quoted C++ guidelines apply in this case. There is no repetition of the typename and the function call doesn't give any clues to the reader indicating what type should be expected. This would require the reader to lookup the function in the header files to figure out what object is being used. Unless the other reviewers disagree I would prefer using `DofTransformation *` (adding the `const` keywords is fine)....</small>

<a href='https://github.com/mfem/mfem/pull/3541' target='_blank'>View Comment</a>