---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-08-12
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4491
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/4491' target='_blank'>flux-framework/flux-core#4491</a>.

<p>python: convert jobid arguments in the API to JobID</p><small>At least some Flux Python API calls that take a jobid expect an integer jobid and do not take any other jobid representations documented in [RFC 19](https://flux-framework.readthedocs.io/projects/flux-rfc/en/latest/spec_19.html). This is slightly inconvenient, and there probably isn't a good reason that these functions can't be changed to attempt `JobID(jobid)` on these args such that all jobid representations are accepted as valid arguments....</small><a href='https://github.com/flux-framework/flux-core/issues/4491' target='_blank'>View Comment</a>