---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/5295043?"
user: johannjc
date: 2023-02-23
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/843
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/johannjc' target='_blank'>johannjc</a> open issue <a href='https://github.com/hypre-space/hypre/issues/843' target='_blank'>hypre-space/hypre#843</a>.

<p>questions about cudaDeviceSynchronize and Struct[Set/Get]BoxValues</p><small>I'm finding it necessary to add a call to cudaDeviceSynchronize after HYPRE_StructVectorGetBoxValues() when using cuda with fortran following a pattern similar to ex12f_cptr.f - otherwise I occasionally see garbage in the output.  Is this expected - and do I need similar device synchronization calls following SetBoxValues etc...?...</small><a href='https://github.com/hypre-space/hypre/issues/843' target='_blank'>View Comment</a>