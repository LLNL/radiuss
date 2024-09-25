---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-09-24
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5372
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/5372' target='_blank'>flux-framework/flux-core#5372</a>.

<p>32-bit breakage</p><small>In adding a jammy builder, I found that the ubuntu 386 builder hasn't been finding some of our issues on 386.  I fixed a few 32-bit issues that had a clear source in #5370, but the full check kicked out quite a lot of errors and failures, and failed to even report from some of the tests.  This is a tracking issue for drawing these down, `make recheck` output below for at least a trace on some of the issues:...</small><a href='https://github.com/flux-framework/flux-core/issues/5372' target='_blank'>View Comment</a>