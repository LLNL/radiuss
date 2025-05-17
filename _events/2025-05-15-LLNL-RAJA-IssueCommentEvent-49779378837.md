---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/203895872?"
user: bechols97
date: 2025-05-15
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1832
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/bechols97' target='_blank'>bechols97</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1832' target='_blank'>LLNL/RAJA#1832</a>.

<small>@rcarson3 Yes, the original intention behind this idea is to be used as a device side error handler (though left to be more generic in case there are other use cases). As @MrBurmark mentioned, it would be possible to use a fixed-string object with the message handler. For string literals, you would want some type of fixed-string object / char array to store the string that is later passed to a host side callback. ...</small>

<a href='https://github.com/LLNL/RAJA/pull/1832' target='_blank'>View Comment</a>