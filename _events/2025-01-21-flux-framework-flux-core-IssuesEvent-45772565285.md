---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2025-01-21
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6560
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/6560' target='_blank'>flux-framework/flux-core#6560</a>.

<p>`parent-uri` attribute set with `flux run flux start --test-size=`</p><small>The detection of whether the current instance has a parent in order to set the `parent-uri` attribute currently relies on whether `FLUX_JOB_ID` is set in the environment. This doesn't always work because `FLUX_JOB_ID` can leak from the environment as is the case for `flux run flux start -s 4` for example. (This is exercised by the inception tests)...</small><a href='https://github.com/flux-framework/flux-core/issues/6560' target='_blank'>View Comment</a>