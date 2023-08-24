---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/44277022?"
user: jwhite242
date: 2023-08-23
repo_name: LLNL/maestrowf
html_url: https://github.com/LLNL/maestrowf/commit/0442e1e0914077612d51d09fe172e3a75a24c0ca
repo_url: https://github.com/LLNL/maestrowf
---

<a href='https://github.com/jwhite242' target='_blank'>jwhite242</a> pushed to <a href='https://github.com/LLNL/maestrowf' target='_blank'>LLNL/maestrowf</a>

<small>Add packaging as explicit dependency and tweak flux adapter version checking (#427)

* Adds packaging to toml file as it is now a required non-dev dependency.  Version is constrained to >=22.0 to reflect removal of LegacyVersion which can be returned from parse_version in older packaging versions.
* Improve robustness of flux adapter version error handling by testing against base_version to allow pre-release builds to succeed.
* Add version comparison unit tests for both full and base_version variants</small>

<a href='https://github.com/LLNL/maestrowf/commit/0442e1e0914077612d51d09fe172e3a75a24c0ca' target='_blank'>View Commit</a>