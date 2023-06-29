---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2023-06-28
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5210
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/5210' target='_blank'>flux-framework/flux-core#5210</a>.

<small>Well, my thinking is that the user intends to send SIGUSR1 to cause some application behavior, e.g. a restart dump. It might be better to ignore the signal in this case rather than terminating the job before it starts. However, this case is pretty unlikely since a user won't be sending this kind of control signal so early, so I'm fine with terminating the job shell for now since that's much simpler, and we'll see if we get any bug reports....</small>

<a href='https://github.com/flux-framework/flux-core/issues/5210' target='_blank'>View Comment</a>