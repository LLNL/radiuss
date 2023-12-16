---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/35237779?"
user: JustinPrivitera
date: 2023-12-15
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1200
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/JustinPrivitera' target='_blank'>JustinPrivitera</a> commented on issue <a href='https://github.com/LLNL/conduit/issues/1200' target='_blank'>LLNL/conduit#1200</a>.

<small>Hi @ibaned. This is possible already, with a couple caveats. The other option you will want to include is `opts["mesh_name"] = "mymeshname";`. You can put whatever name you like there (so the cycle number could go there). The silo writer will prepend that name to the multimesh, multivar, and multimaterial names. It will also place information for domains inside of a directory with that name. Therefore, the only place where information might be clobbered in ensuing writes would be the cycle and time that live inside the root file. I wonder how easy it would be to work with a database stored in this way in a tool like VisIt? I expect you would get a giant list of meshes, and VisIt wouldn't be able to interpret that as a timeseries....</small>

<a href='https://github.com/LLNL/conduit/issues/1200' target='_blank'>View Comment</a>