---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-09-08
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1066
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1066' target='_blank'>flux-framework/flux-sched#1066</a>.

<small>We never tested on Debian 11 in CI. I added support for Debian 12 in addition to our Ubuntu focal and Jammy containers, and since I was doing Bionic when I set the cmake stuff up, I just grabbed a binary cmake for basically all of them which is a newer version.  A debian 11 container using the same dockerfile as our bookworm container should work just fine, except for the python{,3}-yaml rename.  I remember testing with lower cmakes, but must not have after changing the version matching for python.  I think I can fix it so it will work with 3.18, but I have to think through how to get us the correct version constraint without the convenience syntax (haven't had to do it in a good while)....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1066' target='_blank'>View Comment</a>