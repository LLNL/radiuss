---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13872149?"
user: watson6282
date: 2023-09-12
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/5448
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/watson6282' target='_blank'>watson6282</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/5448' target='_blank'>flux-framework/flux-core#5448</a>.

<small>I think the reason the test does not work is that that is how it is supposed to work.  I've done some web searches.  From that I conclude that Bash's errexit has a lot of historical baggage and, in this case, is probably buggy.  I think that errexit is not supposed to apply to the BASH_ENV processing even when turned on via the bash command line option.  However, a particular builtin Bash command causes the errexit processing to become active if turn on.  It just some happens that one of the profile.d scripts uses that command.  Once active, the next unchecked failure of a command leads to bash exiting....</small>

<a href='https://github.com/flux-framework/flux-core/pull/5448' target='_blank'>View Comment</a>