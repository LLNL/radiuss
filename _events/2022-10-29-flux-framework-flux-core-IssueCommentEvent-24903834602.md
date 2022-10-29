---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2022-10-29
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/4737
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/4737' target='_blank'>flux-framework/flux-core#4737</a>.

<small>We have a nice "class" in libflux for operating on a `flux_msg_t`.  You'd want to generate that as completely as possible in the target language to minimize the amount of manual coding labor neededf or each target.  I was thinking this is at odds with the layering we have in flux-core, where we serialize a message object first to an array of blobs, then hand that off to another abstract layer (which is either zeromq, or the local connector)...</small>

<a href='https://github.com/flux-framework/flux-core/pull/4737' target='_blank'>View Comment</a>