---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/1281144?"
user: aragilar
date: 2022-12-11
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/233
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/aragilar' target='_blank'>aragilar</a> open issue <a href='https://github.com/LLNL/sundials/issues/233' target='_blank'>LLNL/sundials#233</a>.

<p>Correct usage of SUNContext_Free</p><small>From https://sundials.readthedocs.io/en/latest/sundials/SUNContext_link.html#c.SUNContext_Free it seems that freeing the context can fail according to the docs (looking at the code, 0 is always returned). If the return value were to be non-zero, what are users supposed to do (e.g. retry freeing at some later point, leak the memory)? This differs from https://sundials.readthedocs.io/en/latest/cvode/Usage/index.html#c.CVodeFree and from the normal POSIX `free`, both of which do not return a status code....</small><a href='https://github.com/LLNL/sundials/issues/233' target='_blank'>View Comment</a>