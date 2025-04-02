---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2025-04-01
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/commit/b7e28c8d63ebe5a75efd1adb8c8027d547427b5a
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> pushed to <a href='https://github.com/visit-dav/visit' target='_blank'>visit-dav/visit</a>

<small>Revert "regen to make py funcs static"
This failed because of the pseudo-inheritence some of our state
objects (meta data) support. In order for those objects to work
correctly, they need to be able to call or use some of the base
class's getattro/setattro and _methods

This reverts commit 6393406d0fdc0eac011fd0d601d8b1ebf491b0d2.</small>

<a href='https://github.com/visit-dav/visit/commit/b7e28c8d63ebe5a75efd1adb8c8027d547427b5a' target='_blank'>View Commit</a>