---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/8368499?"
user: ofaaland
date: 2022-12-06
repo_name: LLNL/scr
html_url: https://github.com/LLNL/scr/pull/520
repo_url: https://github.com/LLNL/scr
---

<a href='https://github.com/ofaaland' target='_blank'>ofaaland</a> commented on issue <a href='https://github.com/LLNL/scr/pull/520' target='_blank'>LLNL/scr#520</a>.

<small>@adammoody OK, I confirmed that the scr flux launcher calls a flux-provided python interface to launch the job, and that interface requires we provide # of nodes, # of tasks per node, etc. explicitly.  Since the scr launcher launchruncmd() takes a command line type string or a list of strings (ie argv) as its input, this means that by using the flux python interface to launch, we have to parse the user's args to extract nodes, tasks, etc....</small>

<a href='https://github.com/LLNL/scr/pull/520' target='_blank'>View Comment</a>