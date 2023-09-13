---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2023-09-12
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3865
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3865' target='_blank'>mfem/mfem#3865</a>.

<small>I noticed the same thing a few weeks back and it seems like the issue is not enough space on the runner image, and the attempt to free up space in the workflow at https://github.com/mfem/mfem/blob/master/.github/workflows/build-container.yaml#L40 is probably insufficient. I found two popular GitHub Actions for this problem in the marketplace: https://github.com/marketplace/actions/maximize-build-disk-space and https://github.com/marketplace/actions/free-disk-space-ubuntu. I don't know how to test out such a change through a PR but would think either of these could be a potential solution....</small>

<a href='https://github.com/mfem/mfem/issues/3865' target='_blank'>View Comment</a>