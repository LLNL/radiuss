---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5295043?"
user: johannjc
date: 2023-03-03
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/843
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/johannjc' target='_blank'>johannjc</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/843' target='_blank'>hypre-space/hypre#843</a>.

<small>I think my confusion - stems from the fact that the hypre_SStructPVectorSetBoxValues routine in sstruct_vector.c has a call to hypre_SyncCudaDevice(hypre_handle()) that is absent in the corresponding routine for the struct interface (struct_vector.c).  So following the sequence of calls in the ex12f_cptr.f (which uses the sstruct interface) but in a simpler problem that uses the Struct interface - leads to a synchronization/corruption error.  This can be solved by putting in additional sync calls before/after set/get box values.  Perhaps the documentation should clarify whether or not users need to manually sync gpu/cpu memory.  I can imagine use cases where this synchronization would be unneccessary - especially in the corresponding routines that don't set values a box at a time......</small>

<a href='https://github.com/hypre-space/hypre/issues/843' target='_blank'>View Comment</a>