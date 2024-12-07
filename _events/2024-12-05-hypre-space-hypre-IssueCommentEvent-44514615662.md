---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20098718?"
user: waynemitchell
date: 2024-12-05
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1191
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/waynemitchell' target='_blank'>waynemitchell</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1191' target='_blank'>hypre-space/hypre#1191</a>.

<small>I've not seen this particular issue when compiling with sycl. I notice from your `make` output that the included `assert.h` is grabbing a header file from `sycl/stl_wrappers`, which I don't seem to have on the Intel systems that I'm running on. The error seems to indicate that this `assert.h` implementation is including some C++ templating stuff under the hood, but we have this included inside an extern C block. You could try wrapping `#include <assert.h>` statement with an extern C++ block and see if that fixes the issue....</small>

<a href='https://github.com/hypre-space/hypre/issues/1191' target='_blank'>View Comment</a>