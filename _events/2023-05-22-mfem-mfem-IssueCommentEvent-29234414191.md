---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/114775781?"
user: hughcars
date: 2023-05-22
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3672
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/hughcars' target='_blank'>hughcars</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3672' target='_blank'>mfem/mfem#3672</a>.

<small>Running with `make ex6p -j6 && mpirun -np 2 ex6p -m ../../data/p2_prism.msh -o 2 -h1` appears to adapt fine, but running without `-h1` namely using the RT smoothed flux space, triggers errors of missing indices in the `inv_index` of `NCMesh::NCList::LookUp(int, int*)`. So the issue appears to be related explicitly to RT meshes on prism elements of order 2 and greater. The failing index 5 appears to be generated in `ParFiniteElementSpace::UnpackDof`....</small>

<a href='https://github.com/mfem/mfem/issues/3672' target='_blank'>View Comment</a>