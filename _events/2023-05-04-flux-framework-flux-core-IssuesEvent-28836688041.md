---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2023-05-04
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5148
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5148' target='_blank'>flux-framework/flux-core#5148</a>.

<p>prevent or mitigate jobs writing large files to kvs stdio</p><small>A production flux instance became unresponsive recently because the KVS was incapacitated trying to return the output eventlog for a job. The job had apparently gone haywire and was writing the same line of output continuously for some time (I think we estimated about 7 million lines). The kvs was unresponsive for the most part (listing keys seemed to work, but not fetching anything, though I could be mistaken about that)...</small><a href='https://github.com/flux-framework/flux-core/issues/5148' target='_blank'>View Comment</a>