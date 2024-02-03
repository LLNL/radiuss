---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/26631700?"
user: sebastiangrimberg
date: 2024-02-02
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4106
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/sebastiangrimberg' target='_blank'>sebastiangrimberg</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4106' target='_blank'>mfem/mfem#4106</a>.

<small>That's exactly right about the use case I have in mind. I can be assured that I won't ever call `Memory::Read` or `Write` inside a parallel region with the device memory class, but I do want to be able to call it with the host class in some coarse-grained cases. One use case is to be able to call `FiniteElementSpace::GetElementDofs` or `Mesh::GetElementTransformation` inside an OpenMP parallel region, used to set up a data structure which will eventually (outside of the OpenMP loop) be used on the GPU....</small>

<a href='https://github.com/mfem/mfem/issues/4106' target='_blank'>View Comment</a>