---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1194526?"
user: cyrush
date: 2024-12-13
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/7bdd16bc4204a33a76941ddd417cfa0bba86f84b
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/cyrush' target='_blank'>cyrush</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Avoid relinking python modules on every build (#20127) (#20130)

This fixes the bug where python modules would be re-linked on every
build causing the visitmodule to be deleted by the pip setup command.

This change sets up usage requirements using an INTERFACE target for
*_py_setup targets which is then linked to the dependent targets to prevent
this from happening.

Co-authored-by: kwryankrattiger <80296582+kwryankrattiger@users.noreply.github.com></small>

<a href='https://github.com/visit-dav/visit/commit/7bdd16bc4204a33a76941ddd417cfa0bba86f84b' target='_blank'>View Commit</a>