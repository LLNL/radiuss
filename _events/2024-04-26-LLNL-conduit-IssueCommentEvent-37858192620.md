---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/45609916?"
user: gunney1
date: 2024-04-26
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/989
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/gunney1' target='_blank'>gunney1</a> commented on issue <a href='https://github.com/LLNL/conduit/issues/989' target='_blank'>LLNL/conduit#989</a>.

<small>@cyrush Just getting back to this.  I'm still interested in this feature.  I'd like to have variations to `execute` that use `MPI_Waitsome` and `MPI_Testsome`.  It should be caller's choice.  Testsome is used when I'm not willing to wait, but I will take whatever has completed.  None if that's the case.  Waitsome is used when I'm willing to wait the minimum time to get at least one completion.  I'm not willing to wait for all to finish.  In my implementation, I have parameter `bool atLeastOne`, that says whether I'm willing to wait for at least one to complete.  The options would allow me to maximize the amount of local computation I can do while waiting....</small>

<a href='https://github.com/LLNL/conduit/issues/989' target='_blank'>View Comment</a>