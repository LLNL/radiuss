---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-11-27
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/47780
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/spack/spack/pull/47780' target='_blank'>spack/spack#47780</a>.

<small>The following issue is probably an issue with hypre's build system, not hypre's Spack package -- I just noticed it when testing this PR: looking at the hypre build log from Spack, I see that the hypre-internal `blas` and `lapack` directories are built and linked into `libHYPRE.a` even when the `+lapack` variant is used. I think hypre functions do not actually call these hypre-internal `blas` and `lapack` functions, so the behavior is correct -- there's just redundant compilation and linking of the hypre-internal `blas` and `lapack`....</small>

<a href='https://github.com/spack/spack/pull/47780' target='_blank'>View Comment</a>