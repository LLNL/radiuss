---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/76020022?"
user: adam-sim-dev
date: 2025-04-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4813
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/adam-sim-dev' target='_blank'>adam-sim-dev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4813' target='_blank'>mfem/mfem#4813</a>.

<small>> `MFEM_VERIFY/ASSERT` errors should not be ignored. You need to debug the code and find the real source of the problems. One common source of troubles spuriously appearing depending on the coefficient values is the sparsity pattern of the matrices. If you assemble/finalize matrix with `skip_zeros`, small value entries are eliminated, which can be due to the value of the coefficient. Turning off `skip_zeros` should solve this....</small>

<a href='https://github.com/mfem/mfem/issues/4813' target='_blank'>View Comment</a>