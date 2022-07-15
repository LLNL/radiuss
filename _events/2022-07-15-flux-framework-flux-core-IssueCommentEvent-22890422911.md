---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2022-07-15
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/4383
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/4383' target='_blank'>flux-framework/flux-core#4383</a>.

<small>talked to @garlick, we both agree that this has become more complicated than either of as initially imagined.  So we're going to backtrack.  We're going to go with the timer loop idea that I originally proposed.  But we'll create a special internal flag like KVSTXN_NO_PUBLISH or something like that, where it will not publish the setroot event after a transaction has completed....</small>

<a href='https://github.com/flux-framework/flux-core/pull/4383' target='_blank'>View Comment</a>