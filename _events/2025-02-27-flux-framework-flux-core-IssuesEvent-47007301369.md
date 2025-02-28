---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-02-27
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6668
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6668' target='_blank'>flux-framework/flux-core#6668</a>.

<p>set enough information in prolog/epilog environment to determine node rank in job</p><small>A prolog or epilog script may need to determine which index the current node was in the job's hostlist. For example, there may need to be some setup run on the first node of the allocation and not elsewhere. Currently, this information is not set by the perilog.so plugin when launching the prolog or epilog, so the script would need to do something like `flux hostlist  $FLUX_JOB_ID` to get the job's hostlist, and manipulate from there. This isn't scalable, however, since this represents an RPC to the job-list module on rank 0 from every node of the job....</small><a href='https://github.com/flux-framework/flux-core/issues/6668' target='_blank'>View Comment</a>