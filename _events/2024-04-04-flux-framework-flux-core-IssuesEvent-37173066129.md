---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-04-04
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5859
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5859' target='_blank'>flux-framework/flux-core#5859</a>.

<p>flux-resource: exponential time complexity processing drained ranks</p><small>Problem: The `flux.resource.ResourceStatus` class builds a set of `DrainInfo` objects internally based on the `resource.status` response. The `get_drain_info()` method then offers a way to looking the `DrainInfo` object for any given drained rank. The lookup iterates the list of `DrainInfo` objects, testing for membership in each entry's `ranks` idset. When there are a lot of drain entries in the `resource.status` response, this results in an exponential performance issue since each drained rank has to iterate many `DrainInfo` entries testing for its own membership with `idset_test()`. As can be seen here, >80s are spent in `idset_test` alone for this testcase (5000 drained ranks):...</small><a href='https://github.com/flux-framework/flux-core/issues/5859' target='_blank'>View Comment</a>