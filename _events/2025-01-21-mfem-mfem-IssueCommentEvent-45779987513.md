---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/25757109?"
user: nmnobre
date: 2025-01-21
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4496
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/nmnobre' target='_blank'>nmnobre</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4496' target='_blank'>mfem/mfem#4496</a>.

<small>I've had the chance to investigate the seemingly arbitrary rebuilds: they are not arbitrary and it's not a bug. They happen if `MFEM_GIT_STRING` changes, because this is injected into the configuration files, on which the normal build target depends on. So, if you had a clean working tree, then modify an existing file (the working tree is now dirty), and then change `data` in any way (just `touch` suffices, but in practice you need to add/remove a file) triggering a reconfigure on `make`, `MFEM_GIT_STRING` is recomputed and a rebuild happens. If your working tree is already dirty, making more changes to new/existing files in `data` won't trigger a rebuild. As soon as you commit or restore though (cleaning the working tree again), then a rebuild will happen if you add/remove a file in `data` and then `make`. Note adding a new file doesn't make the working tree dirty (because it'll be untracked), removing an existing one does - but again to trigger a rebuild the user would need to additionally add/remove a file. I hope that makes things clearer. :) TLDR: it'll very seldomly happen if at all....</small>

<a href='https://github.com/mfem/mfem/pull/4496' target='_blank'>View Comment</a>