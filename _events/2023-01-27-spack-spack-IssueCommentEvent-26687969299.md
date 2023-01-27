---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4886803?"
user: cgmb
date: 2023-01-27
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/31581
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/cgmb' target='_blank'>cgmb</a> commented on issue <a href='https://github.com/spack/spack/issues/31581' target='_blank'>spack/spack#31581</a>.

<small>It's fairly straightforward to detect the amdgpu_target. There's a simple [`amdgpu-arch`](https://github.com/llvm/llvm-project/tree/009048810ac635a7ad6c5f788d537172418b6054/clang/tools/amdgpu-arch) tool in the clang repo that shows exactly how it can be done. It just depends on rocr (hsa-rocr-dev). If you want to avoid installing rocr on systems that don't have an AMD GPU at all, you could check if `/dev/kfd` exists before installing it....</small>

<a href='https://github.com/spack/spack/issues/31581' target='_blank'>View Comment</a>