---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/186343229?"
user: Arlie-Capps
date: 2025-03-20
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/commit/b13b1ec29a6e5cf918de50c44ff2fce15bc222a3
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/Arlie-Capps' target='_blank'>Arlie-Capps</a> pushed to <a href='https://github.com/LLNL/conduit' target='_blank'>LLNL/conduit</a>

<small>Use std::function for memory handler callbacks (#1366)

Change Conduit's memcpy, memset, alloc, and free handlers from function pointers to std::function.  This will allow these handlers to have local state, increasing the flexibility and power to allow on-the-fly creation of new handlers.  The change is backwards-compatible because you can assign a function pointer to a std::function.

---------

Co-authored-by: Cyrus Harrison <cyrush@llnl.gov></small>

<a href='https://github.com/LLNL/conduit/commit/b13b1ec29a6e5cf918de50c44ff2fce15bc222a3' target='_blank'>View Commit</a>