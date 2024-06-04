---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-06-03
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1214
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/1214' target='_blank'>flux-framework/flux-sched#1214</a>.

<p>does resource.acquire marking a node UP trigger a scheduling loop?</p><small>Problem: I was checking to make sure that `resource.acquire` marking a node DOWN did not trigger a scheduling loop, and I can't seem to find how marking a node UP triggers one, given that `resource.acquire` is handled by the resource module and there doesn't seem to be a way for resource to signal qmanager to run the loop.  It must - somehow.  Can someone point out the mechanism?...</small><a href='https://github.com/flux-framework/flux-sched/issues/1214' target='_blank'>View Comment</a>