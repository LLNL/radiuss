---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2024-12-12
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/commit/080241084c393ad905c93a0ee4fbd20f149a7850
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> pushed to <a href='https://github.com/LLNL/maestrowf' target='_blank'>LLNL/maestrowf</a>

<small>Update study configuration during execution (#445)

Add the ability to change some of a study's configuration during execution, including:
   * rlimit (restart limit)
   * throttle
   * sleep

Implementation works like cancel, taking paths to executing study workspaces. Configuration parameters can be updated either via an interactive prompt for each study workspace given, or using explicit/repeated keyword arguments for each configuration parameter.

Current Limitations:
   * rlimit is a per step configuration, but it is only set globally in current implementation
   * If a study is no longer running, updating rlimit will not yet resume the study to account for any increases

Adds termynal to the docs to improve readability of interactive cli commands and their outputs</small>

<a href='https://github.com/LLNL/maestrowf/commit/080241084c393ad905c93a0ee4fbd20f149a7850' target='_blank'>View Commit</a>