---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1194526?"
user: cyrush
date: 2024-11-18
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/commit/289f76bd22608f022baafe589ce562e335c7d693
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/cyrush' target='_blank'>cyrush</a> pushed to <a href='https://github.com/LLNL/conduit' target='_blank'>LLNL/conduit</a>

<small>Avoid relinking python modules on every rebuild (#1334)

Avoid rerunning `conduit_python_py_setup`'s `pip install` command on
every invocation of `make` or `ninja` by recording its last execution
time with an output time stamp file.  Whenever it does rerun, such as
when an input file changes, relink dependent python modules since the
`pip install` command wipes out its `--target` directory.  This can be
achieved by making `conduit_python_py_setup` an INTERFACE library that
propagates the time stamp file as a link dependency of dependent python
modules through `INTERFACE_LINK_DEPENDS`.</small>

<a href='https://github.com/LLNL/conduit/commit/289f76bd22608f022baafe589ce562e335c7d693' target='_blank'>View Commit</a>