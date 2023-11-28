---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16548275?"
user: rfalgout
date: 2023-11-27
repo_name: hypre-space/hypre
html_url: https://github.com/hypre-space/hypre/issues/1015
repo_url: https://github.com/hypre-space/hypre
---

<a href='https://github.com/rfalgout' target='_blank'>rfalgout</a> commented on issue <a href='https://github.com/hypre-space/hypre/issues/1015' target='_blank'>hypre-space/hypre#1015</a>.

<small>We have reference counters in some of the matrix/vector objects in hypre.  I wonder if we should expose this to users somehow so they can create persistent references to objects and better manage memory.  The simplest thing we could do for now is implement a `GetObjectRef` call for all matrices and vectors.  This would maintain backward compatibility and I think it would help Tucker out.  Basically, this call (instead of `GetObject`) would return an object that must be freed separately at some point.  So here both the IJDestroy and the ParDestroy would have to be called (in any order)....</small>

<a href='https://github.com/hypre-space/hypre/issues/1015' target='_blank'>View Comment</a>