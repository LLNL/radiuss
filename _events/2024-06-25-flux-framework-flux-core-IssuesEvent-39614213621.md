---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2024-06-25
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6042
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/6042' target='_blank'>flux-framework/flux-core#6042</a>.

<p>python: `jobspec.setattr()` should probably default to `attributes.system` like the `--setattr` command line option </p><small>A user was trying to set a jobspec attribute via the Python bindings using documentation for the command line, which indicated to use `--setattr=key`. However, `--setattr` defaults to `attirbutes.system` whereas `jobspec.setattr()` defaults to just `attributes`. This led to the job being rejected for the extra `key` in the `attributes` section....</small><a href='https://github.com/flux-framework/flux-core/issues/6042' target='_blank'>View Comment</a>