---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/1194526?"
user: cyrush
date: 2023-03-11
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1076
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/cyrush' target='_blank'>cyrush</a> closed issue <a href='https://github.com/LLNL/conduit/issues/1076' target='_blank'>LLNL/conduit#1076</a>.

<p>DataArray<T>::diff string comparison error</p><small>The diff method does not appear to compare strings properly if a string has been overwritten into a node that already had a longer string. I assume that it saw that it did not have to reallocate and it stores "quad\0" into the existing buffer. Then diff() subtracts 1 off the end of the char buffer length but that does not reflect the length of the string. So, we end up comparing "quad" vs "quad\0on" and the comparison fails....</small><a href='https://github.com/LLNL/conduit/issues/1076' target='_blank'>View Comment</a>