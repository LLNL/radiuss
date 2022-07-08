---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/39026551?"
user: godjos
date: 2022-07-07
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/670
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/godjos' target='_blank'>godjos</a> open issue <a href='https://github.com/hypre-space/hypre/issues/670' target='_blank'>hypre-space/hypre#670</a>.

<p>Run erro of BuildParFromOneFile</p><small>After hypre-2.24.0, an error occurs when I use BuildParFromOneFile to load my CSR matrix. While debugging, I find that row_starts and col_starts are not null in hypre_CSRMatrixToParCSRMatrix, which leads that the func hypre_ParCSRMatrixCreate uses row_starts and col_starts to count first_row_index. As a result, first_col_diag and last_col_diag are both wrong. I think to reset row_starts and col_starts null is the true way....</small><a href='https://github.com/hypre-space/hypre/issues/670' target='_blank'>View Comment</a>