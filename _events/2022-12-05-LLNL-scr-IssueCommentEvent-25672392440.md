---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/8368499?"
user: ofaaland
date: 2022-12-05
repo_name: LLNL/scr
html_url: https://github.com/LLNL/scr/pull/520
repo_url: https://github.com/LLNL/scr
---

<a href='https://github.com/ofaaland' target='_blank'>ofaaland</a> commented on issue <a href='https://github.com/LLNL/scr/pull/520' target='_blank'>LLNL/scr#520</a>.

<small>@adammoody I think the root of the issue is that for flux, scr is trying to use the flux python interface to launch a job rather than just running "flux mini run ..." as specified by the user.  This saves creating one process, but then requires we parse the command line, in the same way "flux mini" would parse it.  This seems fragile, and therefore a mistake, to me....</small>

<a href='https://github.com/LLNL/scr/pull/520' target='_blank'>View Comment</a>