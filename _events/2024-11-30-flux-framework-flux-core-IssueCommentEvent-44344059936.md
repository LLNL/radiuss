---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-11-30
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6463
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6463' target='_blank'>flux-framework/flux-core#6463</a>.

<small>Is there a way we could create a reproducer for just the `flux archive` failure?  It seems like that ought to be reproducible with a size=1 instance since it's just `flux archive create` writing to the KVS, correct?  Is it maybe something to do with content of the files you are putting in the archive?  In my unsuccessful attempts, I was just getting random bytes from `/dev/urandom` and trying to create an archive with one big "file" in it (up to 10G).   There were hundreds of G available in /tmp....</small>

<a href='https://github.com/flux-framework/flux-core/issues/6463' target='_blank'>View Comment</a>