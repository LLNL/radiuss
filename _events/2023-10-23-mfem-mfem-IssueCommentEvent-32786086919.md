---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2023-10-23
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3938
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3938' target='_blank'>mfem/mfem#3938</a>.

<small>No, I'm not using `GetValue` for exactly the reason you mention. But I had code doing a similar transformation from boundary element to face element on an interior face so that I could call `GetFaceValues`, and that's when I ran into the issue. The end result is that this isn't a bug in the original implementation of `be_to_bfe`, but rather just an error in my use of it which goes beyond the expected use. The PR https://github.com/mfem/mfem/pull/3943 is there to handle the general case for anyone looking for similar functionality....</small>

<a href='https://github.com/mfem/mfem/issues/3938' target='_blank'>View Comment</a>