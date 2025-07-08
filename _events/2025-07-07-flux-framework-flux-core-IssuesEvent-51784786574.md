---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/37929162?"
user: mergify[bot]
date: 2025-07-07
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6890
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/mergify[bot]' target='_blank'>mergify[bot]</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/6890' target='_blank'>flux-framework/flux-core#6890</a>.

<p>python: set the default jobspec environment from `os.environ` in `JobspecV1` `from_*` factory functions</p><small>As discussed in [this comment](https://github.com/fux-framework/flux-core/pull/6858#discussion_r2159680216) in #6858, the `JobspecV1` factory functions should have a default environment set from `os.environ`. This shouldn't break existing usage since the `environment` setter replaces the environment dictionary. This is trivial to add should be a big improvement in the quality of the interface....</small><a href='https://github.com/flux-framework/flux-core/issues/6890' target='_blank'>View Comment</a>