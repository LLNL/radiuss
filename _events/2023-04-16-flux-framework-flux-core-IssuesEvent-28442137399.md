---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2023-04-16
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4801
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/4801' target='_blank'>flux-framework/flux-core#4801</a>.

<p>add flux job purge ID [ID ...][</p><small>Problem: if an INACTIVE job entry in the KVS contains something that prevents a restart from occuring, or is for some reason taking up an outsize amount of space, it may be helpful to remove it.  However manually removing it doesn't purge it from the job manager or from `job-list`.  The manual remove is also a little awkward, e.g.  `flux kvs unlink -R $(flux job --to=kvs ID)`...</small><a href='https://github.com/flux-framework/flux-core/issues/4801' target='_blank'>View Comment</a>