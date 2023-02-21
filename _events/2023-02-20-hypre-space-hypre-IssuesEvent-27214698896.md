---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/5295043?"
user: johannjc
date: 2023-02-20
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/839
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/johannjc' target='_blank'>johannjc</a> open issue <a href='https://github.com/hypre-space/hypre/issues/839' target='_blank'>hypre-space/hypre#839</a>.

<p>hypre_structstencilcreate routine is inconsistent with header and F90 wrapper</p><small>The hypre_structstencilcreate routine defined in struct_stencil.c has 3 arguments - the first two are HYPRE_INT's, but the third is a hypre_index instead of a HYPRE_StructStencil.  I believe hypre_index is 3 ints - or 12 bytes, while the hypre_structstencil is just an 8 byte integer.  This would explain the invalid writing to the 4 byte integer stored in memory following the hypre_structstencil.  ...</small><a href='https://github.com/hypre-space/hypre/issues/839' target='_blank'>View Comment</a>