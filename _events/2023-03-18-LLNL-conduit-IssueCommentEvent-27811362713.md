---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/97253?"
user: mathstuf
date: 2023-03-18
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/pull/1084
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/mathstuf' target='_blank'>mathstuf</a> commented on issue <a href='https://github.com/LLNL/conduit/pull/1084' target='_blank'>LLNL/conduit#1084</a>.

<small>Alternative approach where Catalyst optionally uses an external Conduit (while still providing a stable ABI). With this PR, we could embed the ABI hash into the `catalyst_impl` struct and refuse to call code with a mismatching Conduit ABI (though one may already be SoL by just loading the library, we can at least not make things worse and hopefully indicate that *something* is wrong)....</small>

<a href='https://github.com/LLNL/conduit/pull/1084' target='_blank'>View Comment</a>