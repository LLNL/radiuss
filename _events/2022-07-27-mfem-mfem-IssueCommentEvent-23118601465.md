---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2022-07-27
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3115
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3115' target='_blank'>mfem/mfem#3115</a>.

<small>@Wayne901 In MFEM, there are different types of "matrix-free" operators. There is partial assembly (PA) which stores some coefficient and geometry data at quadrature points, and there are other options. The idea is to use less storage and more computation, but the computation is designed to take advantage of GPU acceleration (e.g. using tensor-product factorizations). In any case, my point is that some kind of matrix-free method is necessary to avoid matrix storage, especially for high-order FEM. With such a method, direct solvers are no longer possible, so iterative solvers are necessary. However, good preconditioners, without access to the matrix entries, are unknown. ...</small>

<a href='https://github.com/mfem/mfem/issues/3115' target='_blank'>View Comment</a>