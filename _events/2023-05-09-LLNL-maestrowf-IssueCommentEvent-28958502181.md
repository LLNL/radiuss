---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2023-05-09
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/issues/416
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> commented on issue <a href='https://github.com/LLNL/maestrowf/issues/416' target='_blank'>LLNL/maestrowf#416</a>.

<small>So I've got a hunch on why you didn't run into the bug: the process i"m using is trying to hook maestro up to the system flux instances rather than installing flux and maestro with the same python (be it system or virtualenv).  Doing it this way vs say using the docker image (if that's what you tested?), the flux job objects get flagged as un-pickleable as they're actually cffi critters.   Another aspect of this fix is starting to lay the ground work for submitting to flux native machines which means lifting the URI requirement in the flux adapters (usually just the one exported by flux when you start an allocation, but optionally manually in the spec).   Let me know if this is what you were doing, or if there was some other install procedure you used; still working on the flux docs in maestro and would love to include your process there too (and feel free to add recipes into the docs yourself too, contributions are very welcome here!)....</small>

<a href='https://github.com/LLNL/maestrowf/issues/416' target='_blank'>View Comment</a>