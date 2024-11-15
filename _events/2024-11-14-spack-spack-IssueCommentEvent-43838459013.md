---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1454251?"
user: ye-luo
date: 2024-11-14
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/45256
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/ye-luo' target='_blank'>ye-luo</a> commented on issue <a href='https://github.com/spack/spack/pull/45256' target='_blank'>spack/spack#45256</a>.

<small>In an application, "cuda" usually refers to enabling features for NVIDIA GPUs. In the case of LLVM, it was a bit vague. Historically, the "+cuda" variant refers to enabling OpenMP offload support on NVIDIA GPUs. To enable this feature in the libomptarget plugin, there is some bitcode compilation that requires nvcc toolchain provided by cudatoolkit. A few years back, this toolchain dependency was removed since bitcode can be compiled by clang directly. With this change, we can make OpenMP offload to NVIDIA GPU feature available regardless of cudatoolkit and nvidia driver existence. Hence, "+cuda" became an unnecessary variant and we don't want to expand it further for "+rocm" or  "+hip". Right now by default, libomptarget enables all the GPUs it supports. If user really needs to disable certain features in libomptarget, it needs a different variant name rather than "+cuda" to avoid confusion....</small>

<a href='https://github.com/spack/spack/pull/45256' target='_blank'>View Comment</a>