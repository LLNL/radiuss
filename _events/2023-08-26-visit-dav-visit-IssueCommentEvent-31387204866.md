---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2023-08-26
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/pull/18642
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/pull/18642' target='_blank'>visit-dav/visit#18642</a>.

<small>The problem with Qt5 on macOS is that it does not support python3. It requires a python2 (for at least QtWebEngine anyways...maybe we should explicitly disable that?). On my macOS 12.6.7, with a *vanilla* `PATH`, I have a `python3` but no `python` or `python2` and that is what Qt is looking for. Now, I have a version 2 python there in `/opt/local/bin`. But, there is *a ton of other stuff* in `/opt/local/bin`. So, I don't want `/opt/local/bin` in my path. So, I added a symlink named `python` in a random dir and added that dir to my path so hopefully it will find that version 2 python...</small>

<a href='https://github.com/visit-dav/visit/pull/18642' target='_blank'>View Comment</a>