---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-12-12
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/41529
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/41529' target='_blank'>spack/spack#41529</a>.

<small>I think when I tried to do something akin to this before I literally quoted every single argument before joining them, such that we could get some of this, but it caused problems with a whole lot of tests.  The problem is we accept both `"spec ~quoted +just because='I felt like it' ^meh"` (which is what we get in configs but almost never the CLI) and `"spec ~" "quoted" "+" "just" "because=I felt like it" ^ meh`  with no way to differentiate, and have for a very long time, so either we end up with heuristics like this (which this one seems to work quite well), we tighten the syntax so we can break the ambiguities, or we need a way to explicitly say "break this spec string apart"/"join these pieces together into a spec" to get the rest of the way around it. If we could require something like "each argument must be a complete token" then it gets substantially simpler since each piece could be validated by itself and horrible abominations like `"gcc ~" 'bootstrap cflags=-O3 +' binutils` could actually be diagnosed. When we looked at it last time, the consensus seemed to be that we were more willing to keep with this pattern than to break one or the other.  This seems to be the best balance I've seen down that road.  ...</small>

<a href='https://github.com/spack/spack/pull/41529' target='_blank'>View Comment</a>