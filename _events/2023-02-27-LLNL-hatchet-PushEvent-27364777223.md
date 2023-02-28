---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/5253432?"
user: slabasan
date: 2023-02-27
repo_name: LLNL/hatchet
html_url: https://github.com/LLNL/hatchet/commit/7431adf61b1f752e84b1e2f6d2721ae8f412c9dd
repo_url: https://github.com/LLNL/hatchet
---

<a href='https://github.com/slabasan' target='_blank'>slabasan</a> pushed to <a href='https://github.com/LLNL/hatchet' target='_blank'>LLNL/hatchet</a>

<small>Refactors Query Language for Thicket (#72)

* Reworks the QL to be more consistent with the paper and to be better for a new tool

* Makes tweaks to the refactored QL to get existing unit tests (minus construction tests) working

* Updates the docstrings for the QL

* Reworks GraphFrame.filter for the QL to use new-style queries

* Adds a conditional in filter() to convert old-style queries to new-style

* Fixes conversion of old-style queries to new-style queries

* Fixes the use of super() for Python 2.7

* Removes query.py since it somehow wasn't previously removed

* Updates license comments for the files in query/

* Adds old-style queries back to __all__ in hatchet.query

* Adds DeprecationWarnings whenever an old-style query is built</small>

<a href='https://github.com/LLNL/hatchet/commit/7431adf61b1f752e84b1e2f6d2721ae8f412c9dd' target='_blank'>View Commit</a>