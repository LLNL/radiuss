---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2421912?"
user: helloworld922
date: 2024-12-06
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4504
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/helloworld922' target='_blank'>helloworld922</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4504' target='_blank'>mfem/mfem#4504</a>.

<small>The default constructor of Hypre no longer calls `Hypre::Initialize`, so even if `mfem::Device`'s destructor is the first to call `Hypre::Finalize` which creates the instance, it will just be effectively a no-op since `Finalize()` will detect that the default state is `State::UNINITIALIZED` for HYPRE < 2.29.0, and will use HYPRE's internal state management for HYPRE >= 2.29.0....</small>

<a href='https://github.com/mfem/mfem/pull/4504' target='_blank'>View Comment</a>