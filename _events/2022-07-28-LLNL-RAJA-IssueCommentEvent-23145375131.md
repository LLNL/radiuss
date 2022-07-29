---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-07-28
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1284
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1284' target='_blank'>LLNL/RAJA#1284</a>.

<small>Good question, the final version of the camp and raja updates I cooked up here don't actually do that, but if as part of the blt update we also unconditionally add the aliases, and protect the creation of them in blt from errors caused by them already existing, then we probably should. It would make it easier to make sure composed projects always get the appropriate targets, but right now we didn't need it so I didn't pop it in....</small>

<a href='https://github.com/LLNL/RAJA/pull/1284' target='_blank'>View Comment</a>