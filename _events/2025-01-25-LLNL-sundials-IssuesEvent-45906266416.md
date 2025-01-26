---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/1281144?"
user: aragilar
date: 2025-01-25
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/652
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/aragilar' target='_blank'>aragilar</a> open issue <a href='https://github.com/LLNL/sundials/issues/652' target='_blank'>LLNL/sundials#652</a>.

<p>Allow custom loggers</p><small>It looks like as part of the refactoring around logging/error handling, the option of being able to specify a function to control where logs go has disappeared. Currently, you can just set a filename to use, whereas previously you could tie it into other logging systems (e.g. Python's logging), or just drop the logs as needed (which you can sort-of do now by configuring the logfile as `/dev/null`). Would it be possible to have a logging version of https://sundials.readthedocs.io/en/latest/sundials/Errors_link.html#c.SUNErrHandlerFn (which appears not to be called for lower priority logs)?...</small><a href='https://github.com/LLNL/sundials/issues/652' target='_blank'>View Comment</a>