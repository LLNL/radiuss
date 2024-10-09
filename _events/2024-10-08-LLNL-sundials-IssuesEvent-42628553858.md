---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/11356722?"
user: Steven-Roberts
date: 2024-10-08
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/590
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/Steven-Roberts' target='_blank'>Steven-Roberts</a> open issue <a href='https://github.com/LLNL/sundials/issues/590' target='_blank'>LLNL/sundials#590</a>.

<p>SUNMatScaleAdd Inefficient for Sparse Matrices</p><small>After working on #584, I noticed the sparse implementation of `SUNMatScaleAdd` has a $O(M N)$ runtime for the same reason identified in #253. Ideally the runtime would be $O(nnz_A + nnz_B)$ (total # of nonzero entries in two matrices being added). This can be attained (or at least close), but this is complicated somewhat by `indexptrs` not necessarily being sorted for each column (assuming CSC). After reviewing the [csparse](https://people.sc.fsu.edu/~jburkardt/c_src/csparse/csparse.c) implementation, on which I think the current algorithm is roughly based, I see two possible approaches to improve `SUNMatScaleAdd` performance that I can test....</small><a href='https://github.com/LLNL/sundials/issues/590' target='_blank'>View Comment</a>