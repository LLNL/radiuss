---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-07-15
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6104
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6104' target='_blank'>flux-framework/flux-core#6104</a>.

<p>flux-cron: cron tasks force use of fork/exec by default</p><small>It appears that flux-cron tasks set a CWD by default before calling `flux_rexec()` thereby requiring the broker fallback to fork/exec instead of using `posix_spawn()`. When the broker RSS is large, this is a huge performance penalty. Also, when using tcmalloc, this causes the forked task to hang in libtcmalloc and the broker hangs waiting for the child to reach exec....</small><a href='https://github.com/flux-framework/flux-core/issues/6104' target='_blank'>View Comment</a>