---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2023-03-29
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5033
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5033' target='_blank'>flux-framework/flux-core#5033</a>.

<p>flux job wait: special exit code when no more waitable jobs</p><small>While working on https://github.com/flux-framework/flux-docs/pull/220 I wanted to write a simple example loop to get jobids and "post process" jobs as they complete.  But AFAICT there's no way to differentiate between a job that exited with 1 and `flux job wait` exiting 1 when there are no more jobs to process.  This is the stupid thing I eventually came up with....</small><a href='https://github.com/flux-framework/flux-core/issues/5033' target='_blank'>View Comment</a>